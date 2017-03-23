---
layout: post
title: "Hello World"
categories: intro
date: 23-09-2015 22:00:00
---
Let's see how this goes...

----
    .text


    .global _start
    _start:


    mov $4, %eax /* write system call */
    mov $1, %ebx /* stdout */
    mov $msg, %ecx
    mov $msgend-msg, %edx
    int $0x80


    mov $1, %eax /* _exit system call */
    mov $0, %ebx /* EXIT_SUCCESS */
    int $0x80


    .data


    msg: .ascii "Hello, world\n"
    msgend:

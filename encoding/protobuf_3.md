# Protobuf 3.0 - 编码

## 1. 前言

Protobuf 是 G 厂开源的序列化数据的方法，可以用来作为通信协议或者存储数据。它采用 IDL 这种中立的方式来描述数据接口，使得不同语言编写的程序可以根据同一接口来相互通信。不同编程语言也可以根据 IDL 的描述来生成对应数据结构，并用来编解码二进制数据流。为此，G 厂为主流开发语言都提供代码生成器（即 protoc ）。

为了更好地了解一些细节，本文将主要描述 Proobuf 3.0 的编码规则。

## 2. 热身

## 2.1 Base-128-bit Varint

## 2.2 Zig-zag

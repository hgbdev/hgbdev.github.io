---
layout: post
title: NestJS - Introduction
date: July 5, 2021
description: Nest (NestJS) là một framework dùng để xây dựng ứng dụng Node.js server-side một cách hiệu quả và dễ dàng mở rộng. Nó sử dụng JavaScript, được xây dựng và hỗ trợ đầy đủ cho TypeScript và kết hơn các yếu tố của OOP (Object Oriented Programming), FP (Functional Programming), và FRP (Functional Reactive Programming).
img: i-rest.jpg # Add image post (optional)
fig-caption: # Add figcaption (optional)
tags: [nestjs, introduction]
---
## Giới thiệu

Nest (NestJS) là một framework dùng để xây dựng ứng dụng Node.js server-side một cách hiệu quả và dễ dàng mở rộng. Nó sử dụng JavaScript, được xây dựng và hỗ trợ đầy đủ cho TypeScript và kết hơn các yếu tố của OOP (Object Oriented Programming), FP (Functional Programming), và FRP (Functional Reactive Programming).

Bên cạnh đó, Nest sử dụng HTTP Server từ các framework như Express (mặc định), nhưng có thể tuỳ chọn cấu hình sử dụng Fastify.

Nest cung cấp mức độ trừu tượng cao hơn các framework Node.js (Express/Fastify), nhưng cũng hiển thị trực tiếp các API của họ cho developer. Cho phép developer tự do sử đụng các third-party module có sẵn.

## Kiến trúc

Trong những năm gần đây, nhờ sự ra đời của Node.js, JavaScript trở thành một ngôn ngữ lập trình đa năng được sử dụng để phát triển cho cả backend và fontend. Tạo ra các project tuyệt vời như Angular, React và Vue, giúp đẩy nhanh trình xây dựng ứng dụng, dễ dàng mở rộng cho các ứng dụng frontend. Tuy nhiên, trong số các thư viện và công cụ hiện tại hỗ trợ cho Node (sever-side) vẫn chưa thể giải quyết hiệu quả vấn đề chính là **Architecture.**

Nest cung cấp một kiến trúc ứng dụng out-of-the-box cho phép developer và team của mình tạo ra các ứng dụng có thể mở rộng, chặt chẽ và dễ dàng maintain. 

## Cài đặt

Để bắt bầu, bạn có thể xây dựng dự án bằng Nest CLI, hoặc clone starter project từ Github.

Để xây dựng dự án với Nest CLI, chạy câu lệnh sau ở command line

```bash
$ npm i -g @nestjs/cli
$ nest new project-name
```

Hoặc clone starter repo từ Github với tuỳ chọn ngôn ngữ TypeScript

```bash
$ git clone https://github.com/nestjs/typescript-starter.git project
$ cd project
$ npm install
$ npm run start
```

Nếu bạn muốn bắt đầu với JavaScript

```bash
$ git clone https://github.com/nestjs/javascript-starter.git project
$ cd project
$ npm install
$ npm run start
```

Bạn cũng có thể cài đặt thủ công với các package sau

```bash
$ npm i --save @nestjs/core @nestjs/common rxjs reflect-metadata
```

Happy codding ^^

Document: [https://docs.nestjs.com/](https://docs.nestjs.com/)

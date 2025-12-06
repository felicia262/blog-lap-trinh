---
title: "Thực hành TCP sockets trong Java"
date: 2025-11-30T12:10:00+07:00
draft: false
tags: ["Java","TCP","Socket"]
categories: ["Java"]
description: "Ví dụ client-server dùng TCP sockets trong Java."
featureImage: "images/martin.jpg"
summary: "Ví dụ client-server đơn giản gửi/nhận chuỗi bằng TCP sockets trong Java."
---

Ví dụ minh họa server lắng nghe cổng, chấp nhận kết nối và đọc dữ liệu từ client.

```java
// Server đơn giản
ServerSocket server = new ServerSocket(5000);
Socket client = server.accept();
BufferedReader in = new BufferedReader(new InputStreamReader(client.getInputStream()));
String line = in.readLine();
System.out.println("Received: " + line);
```

---
title: "Giới thiệu JavaScript cho lập trình mạng (Fetch & WebSocket)"
date: 2025-11-30T12:50:00+07:00
draft: false
tags: ["JavaScript","Fetch","WebSocket"]
categories: ["JavaScript"]
description: "Sử dụng Fetch API và WebSocket trong trình duyệt để tương tác mạng."
featureImage: "images/martin.jpg"
summary: "Sử dụng Fetch API và WebSocket trong trình duyệt: cơ bản và ví dụ."
---

Giới thiệu `fetch()` để gọi API và cách mở kết nối WebSocket từ trình duyệt.

```js
// Ví dụ WebSocket client
const ws = new WebSocket('ws://localhost:8080');
ws.onmessage = (ev) => console.log('Message', ev.data);
```

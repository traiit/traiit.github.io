---
layout: post
title:  "Những điều mình biết về Heroku"
date:   2018-11-01 10:00:00
description: Những điều mình biết về Heroku
meta: Những điều mình biết về Heroku
categories: ["javascript","nodejs"]
---
**Heroku là cái "quái" gì ?** Bạn có thể hiểu đơn giản là dịch vụ cung cấp hosting mà có các gói sử dụng "free" hoặc trả phí $$$.Bài viết
này mình sẽ nói đến những gì mình biết với gói "Free". **Có thể bạn đã biết... **Bạn có thể biết các dịch vụ hosting như hostinger ,000webhost,...nhưng nó hỗ trợ khá ít ngôn ngữ không có Python, NodeJS,Ruby...
Hay các dịch vụ VPS như Vultr, DigitalOcean hay Lightsail của "ông" Amazon ...nhưng bạn phải trả phí $$$.
Bạn có thể deploy app của mình với các ngôn ngữ Node.js, Ruby, Python, Java, PHP, Go, Scala, Clojure "Quá đủ-ý kiến chủ quan ^^"
Lựa chọn "Free" và có thể sử dụng đa dạng nhiều ngôn ngữ như Heroku thì đúng là "Hero" :)
Những điều bạn cần biết với gói "Free"...

<h4> Heroku là cái "quái" gì ?</h4>
<p>Bạn có thể hiểu đơn giản là dịch vụ cung cấp hosting mà có các gói sử dụng "free" hoặc trả phí $$$.Bài viết
này mình sẽ nói đến những gì mình biết với gói "Free".<p>
<h4>Có thể bạn đã biết... </h4>
<p>Bạn có thể biết các dịch vụ <b>hosting</b> như hostinger ,000webhost,...nhưng nó hỗ trợ khá ít ngôn ngữ không có Python, NodeJS,Ruby...</p>
<p>Hay các dịch vụ <b>VPS</b> như Vultr, DigitalOcean hay Lightsail của "ông" Amazon ...nhưng bạn phải trả phí $$$.</p>
<p>Bạn có thể deploy app của mình với các ngôn ngữ Node.js, Ruby, Python, Java, PHP, Go, Scala, Clojure "Quá đủ-ý kiến chủ quan ^^"</p>
<p>Lựa chọn "Free" và có thể sử dụng đa dạng nhiều ngôn ngữ như Heroku thì đúng là "Hero" :)</p>
<h4>Những điều bạn cần biết với gói "Free"...</h4>
<p>Bạn lưu trữ ứng dụng "nhỏ nhỏ" với dung lượng hẳn "500MB"-- "không tính Database nhé".
Vì là <b>Free</b> nên bạn chỉ có 500h/tháng sử dụng...What 500h/tháng ? Hãy tính đã nhé ^^ </p>
<code>Used time = 500h = (500/24 ~ 20.8333) day</code>
<p> Vậy 1 tháng chỉ sử dụng được 20 ngày ? Không nhé, bởi vì hosting của bạn sẽ có 2 chế độ là <b>Run</b> và <b>Sleep</b>.Sau mỗi lượt truy cập mà không có lượt truy cập nào thêm nữa trong 30 phút thì hosting sẽ chuyển sang chế độ <b>Sleep</b> nó sẽ ngủ đến khi nào có lượt truy cập mới và bạn phải đợi nó <b>"Ngáp"</b> (Khởi động lại) trong vài giây để chuyển sang chế độ "Run" hoạt động trở lại và quá trình này cứ lặp lại như vậy sẽ tiết kiệm rất nhiều thời gian sử dụng và với những Project <b>"Khủng"</b> của <b>"Sinh viên "</b> thì nó là quá đủ để dùng cả tháng hay vĩnh viễn đến khi nào heroku đóng cửa ^^</p>
<p>Với mỗi app của bạn thì bạn được cung cấp 1 subdomain <code>*.herokuapp.com</code> hoặc bạn trỏ <code>domain</code> của mình về heroku là ok.Mình sẽ post bài về trỏ domain sau ^^</p>  

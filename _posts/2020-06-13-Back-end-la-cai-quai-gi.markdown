---
layout: post
title:  "Back-end là cái quái gì???"
date:   2020-06-13 00:00:00 +0000
categories: Javascript NodeJS
---
![Mô hình client - server](/assets/9.PNG)
Như đúng tiêu đề mình sẽ giải thích cho các bạn chuẩn bị, mới tìm hiểu *Back-end* hoặc chưa có định hướng trong ngành IT nói chung... Ở bài viết này mình chia sẻ góc nhìn của mình về những khái niệm và trải nghiệm thú vị khi học và làm với back-end.

**Back-end**, để hiểu được nó thì translate có nghĩa là **mặt sau** còn front-end chắc chắn là *mặt trước* rồi ...humm. Đúng vậy, là cái thứ mà người dùng không thể nhìn thấy trên giao diện (front-end) là đằng sau giao diện ấy đang **xử lý** cái quần què gì như cách bạn gõ hay dùng giọng nói để tìm kiếm Google thôi. Người dùng không nhìn thầy mà thật ra méo quan tâm đằng sau nó như nào, chỉ quan tâm nó **phản hồi nhanh hay chậm**, có **chính xác** hay không, có **dễ dùng** hay không?
Ơ thế hiểu nó như là viết mấy cái cộng, trừ, nhân, chia thì có đúng không, nó chẳng khác gì môn lập trình căn bản, dăm ba cái bài toán chẳng áp dụng vào đâu. Đúng! Không hề sai nếu mãi hiểu nó theo cách nhạt nhẽo như vậy...

Tạm dừng khái niệm đó lại đã, mình chia sẻ chút câu chuyện của mình. Mình đến với **bách en** chắc là do số phận, chi phí **nhúng** mỗi mạch thêm vài ba các cảm biến... đói lắm mà **mobile** máy yếu cấu hình đâu mà chạy máy ảo. Thôi thì học **web** mà họ bảo **web** nhan nhản đầy ra học làm gì.
Thôi thì hết lựa chọn rồi, cứ theo đi dù sao cũng 1-2 năm đầu đại học thôi mà. Thấm thoát thì cũng được 2 năm theo **back-end**.

Đầu tiên là thấy mấy anh khóa trên share mấy cái link xem thời khóa biểu, khoan tại sao trường không có mà phải tìm tools để xem? Vì nó khó đọc thật sự, tạo lại 1 bản của riêng thì mất thời gian vch. Thật ra, xử lý logic, toán học đâu nhàm chán chỉ cần có **ý tưởng thực tế** và **cách cận vấn đề** sẽ thấy nó giúp ích ta rất nhiều đúng không? Thế là con bot thời khóa biểu trường ra đời cũng được 400 user (mấy bạn đang dùng cho mình xin lỗi vì mình lười update lắm, mình sẽ update sau hihi) qua project đó mình hiểu thêm được về: **crawl**, **http request**, **xử lý cấu trúc dữ liệu**, **setup server**, telegram api, tạo **cơ sở dữ liệu**, cấu trúc project (**design pattern**). Mấy keyword này google đều không tính phí khi search.

Nói đến **bách en** luôn phải nói đến **cơ sở dữ liệu (database)** hiểu đơn giản là nơi lưu trữ dữ liệu. Hiện nay có 2 loại là sql (Structured Query Language) cơ sở dữ liệu quan hệ và nosql (non relational) cơ sở dữ liệu phi quan hệ. Hệ quản trị cơ sở dữ liệu SQL có thể kể đến như: MySQL, SQL server, postgresql, ... NoSQL điển hình như mongodb hay redis, rethinkDB...

**API (Application Programming Interface)** cái khá phổ biến trong ngành này rồi. Nôm na là 1 ông cấp module, hàm cho các ông khác dùng. Mảng web thì hiểu đơn giản là 4 cái cơ bản là tạo , đọc , cập nhật, xóa (**CRUD**). Mới học thì tiếp cận món này như nào? Ừ thì google tiếp, api về thời tiết, facebook api (viết bài, auto like, chatbot, get ảnh, ...), api chuyển giọng nói sang văn bản, api nhận diện khuôn mặt, ...vô vàn luôn. Hãy thử với api covid làm trang thống kê bắt trend ^^.
 
Sẽ có bạn thắc mắc là các trang web có thể realtime (thời gian thực) như chat, nhận thông báo, ... mà không phải load trang. Từ khóa đây **socket.io**.

**VPS (Virtual Private Server)**

Mình hiểu đơn giản nó là 1 cái máy ảo chạy trên 1 con server nào đó và đặt ở đâu đó trên cái trái đất này và rồi bạn chạy ứng dụng mình trên đó. Học cách kết nối VPS , sử dụng các hệ điều hành như **windows server**, **linux (ubuntu, centos, ...)**. Học sử dụng thao tác dòng lệnh **cmd (Command Prompt)**, sử dụng **terminal**, **deploy** ứng dụng, sử dụng **firewall**, cấu hình **database**, blabla...

Bên trên là quá trình học rồi, còn thực tế thì ... toang.

Git (phần mềm quản lý mã nguồn phân tán). Các bạn cũng biết đấy học thì chỉ có chính mình và đồng đội cũng là chính mình thì lấy đâu **conflict** code chứ trừ Buggy ra. Và rồi đi thực tập mình bỏ nguyên 1 buổi để học sử dụng git một cách nghiêm túc và rồi **conflict** vài lần rồi dần dần cũng sẽ ít gặp theo gian chỉ khi phân công rõ ràng cái này thuộc về **teamwork**. Đẩy lên vài lần rồi chết server! quen thôi .. hãy luôn nhớ test trên local thật kỹ và **env (environment)** môi trường vì bạn chạy local, bản dev hay production có những config riêng cho từng env và khai báo chúng đầy đủ.

Có thể bạn nghĩ cấu trúc dữ liệu, thuật toán chỉ là mấy môn để qua môn thì sai rồi nhé. Không có cuộc thi nào cả, chỉ có **task** và **phải hoàn thành** nên lời khuyên là bạn **hãy học những gì bạn muốn**.

Tóm cái váy lại thì, ở vị trị của 1 dev **back-end** thì cần hiểu các yêu cầu từ leader hay khách hàng. Phải biết ứng dụng mình làm gì? Công nghệ nào cần thiết, hỗ trợ. Cơ sở dữ liệu nào phù hợp. Thuật toán nào tối ưu cho từng phần yêu cầu. Hình dung giao diện để tối thiểu về số request, tốc độ phản hồi và chính xác những yếu tố đố đều ảnh hưởng đến trải nghiệm người dùng, lên kế hoạch và phân công trong team. Vậy các bạn sinh viên mới bắt đầu tiếp cận thì nên làm gì... đó là "try it", **bắt tay vào học** vậy thôi. Thời điểm bài viết này mình chỉ là thằng lập trình quèn với vài dòng chia sẻ về kiến thức nhỏ bé của mình hy vọng nó giúp được các bạn được phần nào <3

***traiIT <3***

# page-jarvis
Jarvis facebook page

## Tổng quan

Tạo kênh hỗ trợ tự động trên facebook page.

1. Khi người dùng yêu cầu hỗ trợ kỹ thuật, tư vấn liên quan đến sản phẩm

2. Yêu cầu tối thiểu: Hiểu được người dùng nói gì (NLU), xử lý được những yêu cầu của người dùng (NLP)

3. Thông báo tới quản trị khi `Jarvis` không thể hỗ trợ được

4. Có khả năng chửi lại khách hàng nếu có những yêu cầu quá đáng.

## Motivation

Help me save job :LOL


## Yêu cầu hệ thống khi cài đặt Jarvis

1. Có Server để chạy Node.js API

2. Cấu hình https trên server (sử dụng: [Letsencrypt](https://letsencrypt.org/))

## Cài đặt

* Bước 1: Tạo facebook app tại địa chỉ [https://developers.facebook.com/apps](https://developers.facebook.com/apps)

* Bước 2: Cấu hình **WIT_TOKEN**, **FB_PAGE_TOKEN**, **FB_VERIFY_TOKEN** & **FB_APP_SECRET** trong file `./config.js` 
và deploy code lên server

* Bước 3: Verify `Webhooks` trên app của facebook

* Bước 4: Thiết kế `NLU` & `NLP` cho [WIT](https://wit.ai/) application.


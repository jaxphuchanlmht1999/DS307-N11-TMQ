# **Đồ án Phân tích dữ liệu truyền thông mạng xã hội - Social Listening: A Research Report on The La Roche-Posay Brand**


## Nhóm 5
   - Trần Minh Quân - 18521288 (Nhóm trưởng)
   - Trần Cao Phát - 18521233

## Trong Git này trình bày cách thu thập dữ liệu về thương hiệu The La Roche-Posay trên sàn thương mại điện tử Shopee, quy trình thu thập gồm 3 bước:
  ### 1. Thu thập các link sản phẩm từ shop official của The La Roche-Posay trên Shopee 
     - link thương hiệu: 1. https://shopee.vn/larocheposay_officialstore
                         2. https://tiki.vn/cua-hang/la-roche-posay-official
  ### 2. Thu thập các thông tin của bình luận người dùng bao gồm:
     - name_user: tên user
     - name_product: tên sản phẩm
     - review_star: đánh giá của người dùng về sản phẩm đó
     - comment: nội dung của bình luận người dùng
     - time_cmt: thời gian người dùng bình luận
     - link_product: đường link sản phẩm
     - link_user: đường link profile User
  ### 3. Thu thập dữ liệu của sản phẩm bao gồm:
     - name_product: tên sản phẩm
     - price_discount: giá của sản phẩm trong lúc khuyến mãi
     - price: giá của sản phẩm
     - rating: đánh giá trung bình của sản phẩm đó
     - purchased: số lượt mua sản phẩm
     - link_product: đường link sản phẩm
     - description: mô tả của sản phẩm
     - total_cmt: tổng lượt bình luận
 ### 4. Thu thập thông tin User
     - user_name: tên người dùng
     - user_link: đường link của user
     - Giới tính*: giới tính của User (dùng mô hình dự đoán)
     
 ### 5. Tường lửa Shopee 
     - Relogin và gửi mail xác nhận => Chưa tìm được cách vượt, chữa cháy bằng cách đăng nhập như bình thường xong reload lại trang
 ### 6. Tường lửa Tiki
     - Kéo thả ảnh sao cho khớp => ít bị ban, chắc do may mắn 😁

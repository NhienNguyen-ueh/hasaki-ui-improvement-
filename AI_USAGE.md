
## Bài tập cá nhân Buổi 2 – Phát triển ứng dụng thương mại điện tử

### 1. Thông tin chung

- **Công cụ AI sử dụng:** ChatGPT
- **Mục đích:** Hỗ trợ học tập, giải thích kiến thức HTML5/CSS3, cải thiện mã nguồn và xử lý các vấn đề trong quá trình phát triển giao diện website.
- **Người thực hiện:** Nguyễn Muội Nhiên 

### 2. Prompt đã sử dụng
**Prompt 1**
Tôi muốn thực hành CSS selector và Box Model trên một thẻ sản phẩm trong website của
mình.
HTML hiện tại:
 <ul class="product-list">
          <li>
            <article class="product">
              <img src="assets/sữa rửa mặt hasaki.jpg" alt="Sữa Rửa Mặt Cetaphil Dịu Lành Cho Da Nhạy Cảm 125ml" width="126" height="126">
              <div class="product__info">
                <span class="product__brand">CETAPHIL</span>
                <h3>
                  <a href="https://hasaki.vn/san-pham/sua-rua-mat-cetaphil-diu-nhe-khong-xa-phong-125ml-moi-101589.html">
                  Sữa Rửa Mặt Cetaphil Dịu Lành Cho Da Nhạy Cảm 125ml
                  </a>
                </h3>
                <span class="product__variant">Phân loại: 125ml</span>
                <div class="product__prices"><strong>185.000đ</strong><del>124.000đ</del></div>
                <div class="product__bottom">
                  <label>Số lượng <input type="number" min="1" max="99" value="1" aria-label="Số lượng sữa rửa mặt"></label>
                  <button class="remove-button" type="button" aria-label="Xóa sữa rửa mặt khỏi giỏ hàng">✕ Xóa</button>
                </div>
              </div>
            </article>
          </li>

Hãy hướng dẫn tôi:
1. Sử dụng element selector và class selector.
2. Sử dụng descendant selector khi phù hợp.
3. Điều chỉnh margin, padding và border.
4. Sử dụng border-radius để bo góc.
5. Định dạng tên và giá sản phẩm.
6. Định dạng liên kết thành nút thao tác đơn giản.

Hãy giải thích sự khác nhau giữa margin và padding.
Giải thích tác dụng của box-sizing: border-box.
Chỉ đưa ra phần CSS cần thiết.
Không thay đổi nội dung hoặc tạo lại toàn bộ HTML.
**Prompt 2** 
Tôi muốn bổ sung hiệu ứng hover và focus cho một nút bấm hoặc liên kết trong website.

Đây là HTML và CSS hiện tại:
 <a class="continue-link" href="https://hasaki.vn/">← Tiếp tục mua sắm</a>
.continue-link{display:inline-block;margin:2px 24px 23px;color:var(--green);font-size:14px;font-weight:700}

Hãy hướng dẫn tôi:
1. Tạo hiệu ứng hover nhẹ.
2. Sử dụng transition để tạo chuyển đổi mượt.
3. Bổ sung focus-visible để hỗ trợ điều hướng bằng bàn phím.
4. Đảm bảo màu chữ và màu nền dễ nhìn.
5. Không làm thay đổi bố cục quá nhiều.

Hãy chỉ đưa ra phần CSS cần thêm hoặc sửa.
Giải thích từng thuộc tính và cách kiểm tra.

### 3. Đánh giá việc sử dụng AI

**Những nội dung AI hỗ trợ tốt:**
- Giải thích các kiến thức HTML5 và CSS3.
- Gợi ý cách tổ chức cấu trúc HTML hợp lý.
- Hướng dẫn sử dụng CSS Selector, Box Model và các hiệu ứng CSS.
- Đề xuất hướng kiểm tra và khắc phục lỗi giao diện.

**Những nội dung cần tự kiểm tra:**
- Không áp dụng toàn bộ mã nguồn AI đề xuất một cách máy móc.
- Kiểm tra tính phù hợp của mã CSS với cấu trúc HTML thực tế.
- Kiểm tra giao diện trên trình duyệt sau mỗi lần chỉnh sửa.
- Điều chỉnh mã nguồn khi kết quả chưa đáp ứng yêu cầu.

### 4. Cam kết của sinh viên

Tôi sử dụng AI như một công cụ hỗ trợ học tập và tham khảo trong quá trình thực hiện bài tập. Tôi chủ động tìm hiểu, kiểm tra, lựa chọn và điều chỉnh các đề xuất của AI để phù hợp với mã nguồn và yêu cầu bài tập.

Tôi chịu trách nhiệm về nội dung mã nguồn và sản phẩm cuối cùng do mình thực hiện.

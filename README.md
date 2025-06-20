**Lưu ý:** Đây chỉ là sản phẩm học tập, không có nhiều giá trị nên độ hoàn thiện sẽ không cao như các Chatbot AI.

**Dự án này có thể Host trên bất kỳ nền tảng cloud nào hỗ trợ tạo App Web sử dụng Flask**

Link trang web đã Host Chatbot bằng PythonAnywhere: https://khuongit24.pythonanywhere.com/ (Closed)

![image](https://github.com/khuongit24/Simple-Chatbot/assets/161446361/2fbe9429-b365-4b08-ac6d-c7598f04c654)


**Lỗi hiện có:**

Tính năng `Tự học hỏi câu trả lời` từ người dùng không hoạt động trên Web(Vẫn còn hoạt động trên **Terminal**).

Thỉnh thoảng chatbot sẽ hiểu sai nội dung câu hỏi.

__CÁCH HOST CHATBOT TRÊN MÁY TÍNH CÁ NHÂN__

**Bước 1:** Cài đặt **Flask**

Đầu tiên, bạn cần cài đặt **Flask**. Bạn có thể làm điều này bằng cách sử dụng **pip**, trên **Terminal** hoặc **Command Prompt**:

Gõ lệnh sau vào **Terminal** hoặc **Command Prompt** -> **Enter**:

```pip install Flask```

**Bước 2:** Click chuột phải vào file **Simple-Chatbot** vừa tải về -> **Terminal**

Hoặc bạn có thể mở **Terminal** từ bên ngoài -> Trong trang **Terminal**, gõ **cd** + đường dẫn đến tệp

Ví dụ: **cd D:\Simple-Chatbot**

Trong trang **Terminal** gõ 

```python app.py```  -> **Enter**

Sau khi khởi chạy, sẽ hiện thông tin như sau:

 * Serving Flask app 'app'
 * Debug mode: on
WARNING: This is a development server. Do not use it in a production deployment. Use a production WSGI server instead.
 * Running on http://127.x.x
Press CTRL+C to quit
 * Restarting with stat
 * Debugger is active!
 * Debugger PIN: 974-xxx-xxx

**Bước 3:** Mở trình duyệt bất kỳ, nhập http://localhost:5000/ hoặc http://127.x.x và bắt đầu sử dụng

__KẾT QUẢ:__

![image](https://github.com/khuongit24/Simple-Chatbot/assets/161446361/134313c9-0f79-445b-9758-9b9c6072f006)

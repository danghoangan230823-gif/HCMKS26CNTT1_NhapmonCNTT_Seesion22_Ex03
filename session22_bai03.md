# Bài 3 : Sử dụng AI an toàn khi xử lý lỗi phần mềm
## BÁO CÁO PHÂN TÍCH (MÔ HÌNH IPO)
1. Input (Đầu vào - Câu trả lời của AI)

- Vấn đề gặp phải: Lỗi "Path not found" khi cài đặt hoặc chạy Python trên hệ thống (Windows/macOS/Linux).
2. Process (Quy trình kiểm chứng thông tin):

Bước 1: Phân tích cú pháp & nguy cơ

- Tách câu lệnh AI đưa ra thành từng thành phần: Cờ (flags), đường dẫn (paths), quyền truy cập (sudo/administrator).

Bước 2: Phụ thuộc hệ điều hành (OS Verification)

- Xác định lệnh AI cung cấp dành cho Windows (PowerShell/CMD) hay macOS/Linux (Bash/Zsh).

Bước 3: Tra cứu & Kiểm chứng thực tế (Fact-Checking)

- Sử dụng toán tử tìm kiếm nâng cao trên các nguồn uy tín:

+ Tìm kiếm bài thảo luận cộng đồng: site:stackoverflow.com "Path not found" python [câu_lệnh_AI]

+ Kiểm tra tài liệu chính thức: site:docs.python.org "PATH"

Bước 4: So sánh & Đối chiếu

- Đánh giá xem câu lệnh từ AI có match với giải pháp chuẩn trên StackOverflow hoặc Docs chính thức hay không.
## 2. Thiết Kế Prompt "Hỏi Ngược Lại" AI (Refusal & Verification Prompt)
Bạn vừa đề xuất câu lệnh sau để sửa lỗi "Path not found": 
`[Dán_câu_lệnh_của_AI_vào_đây]`

Trước khi tôi thực thi câu lệnh này trên Terminal, hãy giải thích chi tiết cho tôi:
1. Phân tích chi tiết từng cú pháp, tham số (flags) và tác động của câu lệnh này lên hệ thống là gì?
2. Câu lệnh này dành cho Hệ điều hành nào (Windows/macOS/Linux) và phiên bản cụ thể nào?
3. Câu lệnh có yêu cầu quyền Administrator/Root không? Nếu có, nó can thiệp vào những thư mục hay tệp tin nào?
4. Những rủi ro có thể xảy ra (mất dữ liệu, xung đột hệ thống, lừa đảo/mã độc) nếu câu lệnh này bị sai cú pháp hoặc do ảo giác (hallucination)?
5. Cung cấp đường dẫn tài liệu chính thức (Official Docs) hoặc nguồn uy tín (như StackOverflow) xác nhận độ an toàn của phương pháp này.



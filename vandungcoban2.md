bước 1: phân tích lỗi
prompt cũ đang viết là "hãy viết một bài chia sẻ về ứng dụng ai trong học tập & nghiên cứu bằng ngôn ngữ [language]. dành cho đối tượng {audience}."

dùng lẫn lộn ngoặc vuông [language] với ngoặc nhọn {audience} làm hàm quét biến hoặc script tự động hóa khó bắt đúng chuẩn tất cả các biến

ai dễ hiểu nhầm dấu ngoặc nhọn {} là cấu trúc mã kiểu json hay biến lập trình chứ không phải chỗ điền chữ thay thế

tên biến viết lẫn tiếng anh chữ thường và thiếu quy chuẩn thống nhất nên khó quản lý khi làm nhiều mẫu

bước 2: đồng bộ biến số
đưa hết về dạng ngoặc vuông với tên tiếng việt viết hoa có gạch dưới cho rõ ràng:

Plaintext

hãy viết một bài chia sẻ về ứng dụng ai trong học tập & nghiên cứu bằng ngôn ngữ [NGÔN_NGỮ] dành cho đối tượng [ĐỐI_TƯỢNG]

bước 3: chạy thử sau khi điền dữ liệu
[NGÔN_NGỮ]: tiếng việt

[ĐỐI_TƯỢNG]: sinh viên năm nhất ngành công nghệ thông tin

prompt sau khi điền:

"hãy viết một bài chia sẻ về ứng dụng ai trong học tập & nghiên cứu bằng ngôn ngữ tiếng việt dành cho đối tượng sinh viên năm nhất ngành công nghệ thông tin"

kết quả chạy thử:

ai giúp sinh viên năm nhất tóm tắt giáo trình dài nhanh hơn và tìm ý tưởng nghiên cứu dễ dàng hơn

khi học lý thuyết khó hiểu có thể bắt ai hỏi ngược lại từng bước để tự nhớ bản chất thay vì học vẹt

nhớ kiểm tra lại thông tin ai trả lời để tránh sai lệch và dùng tiêu chí rõ ràng khi tự chấm bài
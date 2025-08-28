# Phân tích lĩnh vực tuyển dụng nghành CNTT hiện nay

## Thu thập dữ liệu:

- Đọc data từ file output. json

## Trực quan hóa các từ có trong tập dữ liệu

- Xử lý dữ liệu thô từ file data --> Lọc ra rows name của data để phân tích về nghành nghề trong CNTT
- Vẽ tần suất xuất hiện của 20 từ phổ biến

## Xử lý ngôn ngữ tự nhiên

### Tiền xử lý dữ liệu

- Làm sạch dữ liệu
- Tiền xử lý dữ liệu --> Chuẩn hóa text (lowercase, bỏ dấu tiếng Việt, loại bỏ ký tự đặc biệt).
- Loại bỏ stopwords của tiếng Việt + tiếng Anh
- Lemmatization (Chuẩn hóa từ)
- Tokenization (Tách từ)

## Trực quan hóa dữ liệu

- Word Cloud → hiển thị từ khóa về nghành nghề trong CNTT
- Word Frequency / TF-IDF → tìm từ khóa phổ biến
- Network graph → mối quan hệ giữa các từ với nhau
- Bar chart → so sánh tần suất của các nghành nghề.
- Sentiment Analysis → xem thái độ thị trường với từng công nghệ (tích cực/tiêu cực).
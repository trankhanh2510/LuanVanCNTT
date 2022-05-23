# LuanVanCNTT
PHÁT HIỆN ĐƯỜNG LƯỠI BÒ TRONG ẢNH
Nhận dạng đường lưỡi bò (nine-dash-line)

Nêu vấn đề: việc Trung quốc ngang nhiên tự nhận, tự in các ảnh, map có đường lưỡi bò xâm phạm chủ quyền vùng biển việt nam ngày càng nhiều. Đây là một trong những vấn đề hết sức nhạy cảm trên các trang báo, mạng xã hội. Nên việc có một api hoặc model có khả năng nhận dạng chính xác đường lưỡi bò trong phim, ảnh là một thứ cần thiết để sàng lọc những nội dung như này. (https://vnexpress.net/cgv-bi-phat-170-trieu-dong-vi-nhap-phim-co-duong-luoi-bo-4003775.html)

Sử dụng dataset của zalo hackathon public (https://drive.google.com/drive/folders/1_2-h5FMtXyuYcVXfDTxDc5XNWajaAA1f)

Bài viết tham khảo: https://viblo.asia/p/deep-learning-thuat-toan-faster-rcnn-voi-bai-toan-phat-hien-duong-luoi-bo-faster-rcnn-object-detection-algorithm-for-nine-dash-line-detection-bJzKmREOZ9N

API mà zalo đã public: https://zalo.ai/docs/api/nine-dash-line-detector

Sử dụng model: Faster R-CNN và Yolov5
Có sử dụng aug image nhưng chưa tốt.

đánh giá: model detect tương đối tốt với những bản đồ, nhưng vẫn có nhiều chỗ detect bị sai và thiếu. Nhưng việc sử dụng model này để xem xét các ảnh có khả năng cao chứa đường lưỡi bò là hoàn toàn có thể nếu cải thiện thêm.

Link Dataset: https://github.com/hoangvu98/Nine-dash-line-detection

Link Dataset: https://drive.google.com/drive/folders/1_2-h5FMtXyuYcVXfDTxDc5XNWajaAA1f

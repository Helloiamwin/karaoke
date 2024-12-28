# Phục vụ cho đam mê cà kê

App được deploy lên streamlit, phục vụ đam mê âm nhạc của bản thân, khi mà cứ tới quán karaoke là không biết hát bài gì, nên cần một app giúp cho tìm kiếm các bài hát mà mình thích, có thể lọc theo nhiều tiêu chí khác nhau từ đơn ca, song ca, nhạc vui hay buồn, tiết tấu nhanh hay chậm, chủ đề đám cưới hay tình yêu, ...

# Tổ chức dữ liệu
- các bài hát được lưu trong file `data.csv` với các cột đáng chú ý:
    - `tempo`: tiết tấu: nhanh, chậm, ...
    - `mood`: tâm trạng: vui, buồn, ...
    - `theme`: chủ đề: tết, đám cưới, tình yêu, ...

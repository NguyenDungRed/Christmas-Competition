PEN401 — Jingle All the Way (GitHub Pages)

CÁCH HOST:
1. Giải nén thư mục này.
2. Upload index.html, .nojekyll và README.txt lên ROOT của repository GitHub.
   (Không đặt index.html trong một thư mục con.)
3. Vào Settings > Pages.
4. Ở Build and deployment, chọn Deploy from a branch.
5. Chọn branch main và folder /(root), sau đó Save.
6. Mở URL GitHub Pages của repository.

LƯU Ý:
- GitHub Pages tự động tìm file index.html ở thư mục được chọn làm publishing source.
- Nếu muốn truy cập bằng URL dạng /ten-file.html, cần giữ file có đúng tên đó;
  còn URL trang chủ của site vẫn cần index.html.
- Trang hiện được đóng gói theo dạng self-contained, không cần cài thư viện hay build step.

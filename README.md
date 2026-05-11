# DHSG_fuzzy
Vấn đề bạn gặp là gì?
Divergent branches (nhánh phân kỳ) — tức là:

GitHub (remote) có commit mà Codespaces không có
Codespaces có commit mà GitHub không có
→ 2 bên "lệch nhau", Git không biết nên làm gì


3 lệnh đó làm gì?
LệnhTác dụnggit config pull.rebase falseNói với Git: khi pull thì dùng mergegit pull --allow-unrelated-historiesKéo code từ GitHub về, cho phép gộp dù lịch sử khác nhaugit push origin mainĐẩy tất cả lên GitHub


## Bài tập 1: Xây dựng tập mờ

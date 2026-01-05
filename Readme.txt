========================================================================
TÊN ĐỒ ÁN: GK07_Demo 
MÔN HỌC: PHÁT TRIỂN TRÒ CHƠI
PHIÊN BẢN: 1.0
========================================================================

I. THÔNG TIN THÀNH VIÊN NHÓM
------------------------------------------------------------------------
1. Khưu Trùng Dương - 52200154
2. Nguyễn Vĩnh Hưng - 52200097
3. Nguyễn Hòa An    - 52200182

II. VIDEO DEMO (Yêu cầu bắt buộc)
------------------------------------------------------------------------
Link Video (Youtube/Google Drive): 
Google Drive: https://drive.google.com/drive/u/2/folders/1nFajthh6KaGl987RUoogiCnrF8Qg9twJ
Youtube: https://youtube.com/watch?v=ZMxyqX5Qc2I

*** LƯU Ý QUAN TRỌNG:
- Video này đã được để ở chế độ Công khai (Public) hoặc Không công khai (Unlisted).
- Link đảm bảo tồn tại ít nhất 2 tháng kể từ ngày nộp bài.
- Nhóm cam kết không thay đổi nội dung video sau khi hết hạn nộp bài.


III. CẤU TRÚC NỘP BÀI
------------------------------------------------------------------------
Vì nguyên nhân do Elit không đủ dung lượng chứa source nên em đã để nó link drive này

Link drive: https://drive.google.com/drive/folders/1iyZ5CyUrQtzdCas9rEnWSVoT4kKAuSH6?usp=sharing
------------------------------------------------------------------------
Trong thư mục nộp bài bao gồm 2 thành phần chính:
1. File nén "GK07_Demo.zip": Chứa bản Game đã đóng gói (.EXE) để chơi ngay.
2. Thư mục "GK07_Demo": Chứa toàn bộ Source Code (Dự án Unreal Engine).


IV. CÁCH 1: HƯỚNG DẪN CÀI ĐẶT & CHƠI GAME (Bản Build .EXE)
(Dành cho việc trải nghiệm game nhanh chóng)
------------------------------------------------------------------------
Bước 1: Giải nén file "GK07_exe.zip" ra một thư mục riêng.
Bước 2: Truy cập vào thư mục vừa giải nén, tìm file thực thi: "GK07_exe.exe".
Bước 3: Nhấp đúp chuột để chạy game.

* Lưu ý: 
- Lần đầu mở game có thể mất 1-2 phút để load dữ liệu, vui lòng chờ đợi.
- Nếu máy báo thiếu DirectX/Visual C++, vui lòng cài đặt các driver cần thiết.


V. CÁCH 2: HƯỚNG DẪN CHẠY SOURCE CODE (Project Unreal)
(Dành cho Giảng Viên chấm code và cấu trúc dự án)
------------------------------------------------------------------------
Yêu cầu hệ thống:
- Unreal Engine Version: 5.5.4 trở lên
- Visual Studio: 2022

Các bước thực hiện:
Bước 1: Truy cập vào thư mục "GK07_Demo" (Folder chứa Source).
Bước 2: Tìm file khởi động dự án tên là: "GK07_Demo.uproject".
Bước 3: Chuột phải vào file .uproject -> Chọn "Generate Visual Studio project files".
        (Bước này bắt buộc để tạo lại các liên kết hệ thống trên máy mới).
Bước 4: Nhấp đúp vào file "GK07_Demo.uproject" để mở Unreal Editor.
Bước 5: Đợi Editor biên dịch (Compile) shader lần đầu. Sau khi mở xong, nhấn nút "Play" map "Demo" (trong thư mục Midterm) trên thanh công cụ để chạy.

* Khắc phục sự cố (Troubleshooting):
- Nếu gặp lỗi khi mở Source, hãy thử xóa các thư mục: "Binaries", "Intermediate", "Saved" nằm trong folder GK07_Demo, sau đó thực hiện lại từ Bước 3.


VI. HƯỚNG DẪN ĐIỀU KHIỂN (CONTROLS)
------------------------------------------------------------------------
A. ĐIỀU KHIỂN NHÂN VẬT (ON FOOT)
- W, A, S, D: Di chuyển (Movement)
- Chuột (Mouse): Xoay Camera (Look around)
- Space: Nhảy (Jump)
- C: Ngồi (Crouch)

* Chiến đấu & Tương tác:
- Chuột Trái (LMB): Bắn (Shoot)
- Chuột Phải (RMB): Ngắm (Aim)
- Chuột Giữa (MMB): Bật/Tắt Bullet Time (Làm chậm thời gian)
- R: Nạp đạn (Reload)
- X / Z: Đổi vũ khí (Switch Equipment)
- H: Cất vũ khí (Holster Weapon)
- Q: Mở/Đóng túi đồ (Inventory)
- G: Vứt trang bị (Drop Equipment)
- E: Tương tác (Interaction)
- Num 1: Bật/Tắt bảng hướng dẫn (Show/Hide Control Guide)

B. ĐIỀU KHIỂN XE (VEHICLE)
- W: Tăng tốc (Accelerate)
- S: Lùi xe (Reverse)
- A, D: Rẽ Trái / Phải
- Space: Phanh tay (Handbrake)
- Phím 1: Chuyển góc nhìn thứ nhất (First Person Camera)

C. THOÁT
- ESC: HIỆN MENU

VII. CÁC GHI CHÚ KHÁC & TÍNH NĂNG NỔI BẬT
------------------------------------------------------------------------
- Game thuộc thể loại: 3D Survival Shooter / Single-player Battle Royale (PvE)
  (Game bắn súng sinh tồn góc nhìn thứ 3 đấu với AI Enermy)

- Các tính năng đặc biệt đã thực hiện:
  + Cơ chế Gameplay cốt lõi: Xây dựng hoàn thiện nhân vật có thể di chuyển, ngắm bắn, thay đạn và gây sát thương dựa trên các Class cơ bản của Unreal.
  + Hệ thống AI thông minh (Advanced Enemy AI): Kẻ thù có khả năng tuần tra (Patrol), sử dụng thị giác/thính giác (AI Perception) để phát hiện người chơi và tự động điều hướng (Navigation) để truy đuổi và tấn công.
  + Cơ chế chiến đấu (Combat System): Hệ thống vũ khí đa dạng mô phỏng phong cách chiến đấu trên chiến trường, bao gồm ngắm kẻ địch, bắn súng, thay đạn và hiệu ứng sát thương.
  + Môi trường chiến thuật (Tactical Environment): Bản đồ được thiết kế dạng Mini-Sandbox Moutain Winter với các khu vực ẩn nấp vùng núi, 1 nhà nhỏ, yêu cầu người chơi phải di chuyển chiến thuật để không bị AI bao vây, và bị bắn đến hết máu.
  + Hệ thống UI/HUD đơn giản: Hướng dẫn thao tác đầu vào, hiển thị máu, đạn dược, tâm ngắm, Inventory và Menu tương tác trực quan,...

- Các lỗi còn tồn đọng (Known Bugs):
  + Vì là bản demo giới thiệu các thành phần của Unreal Engine nên còn nhiều vấn đề như: Map đơn giản, AI đơn giản, Animation còn hơi cứng....
========================================================================
XIN CẢM ƠN GIẢNG VIÊN ĐÃ XEM VÀ CHẤM BÀI CỦA NHÓM EM Ạ!
========================================================================
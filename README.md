## Run app

 - Bước 1: Tạo môi trường ảo co Python (phiên bản 3.x)
     ## Windows:
     		py -m venv .venv
   - Bước 2: Kích hoạt môi trường:
     ## Windows:
     		.venv\Scripts\activate
     ### Nếu xảy ra lỗi active .venv trên winos run powshell -->Administrator
         Set-ExecutionPolicy RemoteSigned -Force
   - Bước 3: Cài đặt các thư viện cần thiết
     ## Install:
     		pip install -r requirements.txt

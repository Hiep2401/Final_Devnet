- Cách chạy file docker 

- Đầu tiên trên máy ảo ubuntu image thực hiện các lệnh sau:
"apt-get update -y” và “apt-get install -y python-pip"

- Tạo thư mục /usr/src/app/ với câu lệnh “mkdir -p /usr/src/app/”

- Thực hiện tạo thư mục cau6 với "mkdir cau6"

- Sau đó thực hiện pull image để chạy trên dockerhub.com bằng lệnh
"docker pull python:3.7-alpine" có thể chọn cái khác tùy ý

- Sau đó kiểm tra bằng "docker images"

- Thực hiện build bằng lệnh "docker build -t cau6 ."

- Thực hiện run bằng lệnh: docker run -p -d 80:5000 -t cau6 

- Mở trình duyệt truy cập đến địa chỉ: 0.0.0.0


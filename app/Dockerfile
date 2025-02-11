# Sử dụng image base Node.js
FROM node:16

# Sao chép code vào container
COPY . /app

# Chạy lệnh cài đặt
WORKDIR /app
RUN npm install

# Mở port
EXPOSE $APP_PORT

# Chạy ứng dụng
CMD ["npm", "start"]
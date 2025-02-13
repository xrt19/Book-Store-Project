FROM node:22

# Set direktori kerja di dalam container
WORKDIR /app

# Salin seluruh kode aplikasi ke dalam container
COPY . .

# Install dependensi aplikasi
RUN npm install

# Ekspos port yang digunakan aplikasi (misalnya 5173)
EXPOSE 5173

# Perintah untuk menjalankan aplikasi
CMD ["npm", "run", "dev"]
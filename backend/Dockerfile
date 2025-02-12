FROM node:22

# Set direktori kerja di dalam container
WORKDIR /app

# Salin seluruh kode aplikasi ke dalam container
COPY . .

# Install dependensi aplikasi
RUN npm install

# Ekspos port yang digunakan aplikasi (misalnya 3000)
EXPOSE 5555

# Perintah untuk menjalankan aplikasi
CMD ["node", "index.js"]

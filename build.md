Để build được dự án `hexo-theme-butterfly` từ GitHub, bạn cần thực hiện các bước sau đây:

1. **Cài đặt Hexo**:
   Nếu bạn chưa có Hexo, bạn cần cài đặt nó trước. Hexo yêu cầu Node.js và npm.

   ```bash
   npm install -g hexo-cli
   ```

2. **Tạo một dự án Hexo mới**:
   Tạo một dự án Hexo mới hoặc di chuyển vào thư mục dự án hiện có của bạn.

   ```bash
   hexo init my-blog
   cd my-blog
   npm install
   ```

3. **Tải theme Butterfly**:
   Bạn có thể tải theme Butterfly từ GitHub và sao chép vào thư mục `themes`.

   ```bash
   cd themes
   git clone https://github.com/jerryc127/hexo-theme-butterfly.git butterfly
   ```

4. **Cấu hình theme**:
   Mở file `_config.yml` trong thư mục gốc của dự án Hexo và thay đổi giá trị của `theme` thành `butterfly`.

   ```yaml
   theme: butterfly
   ```

5. **Cài đặt các phụ thuộc của theme**:
   Theme Butterfly có thể yêu cầu thêm các package khác. Bạn cần kiểm tra file `package.json` trong thư mục của theme và cài đặt các package cần thiết.

   ```bash
   npm install --save <package-name>
   ```

6. **Cấu hình theme Butterfly**:
   Tùy chỉnh theme theo nhu cầu của bạn bằng cách chỉnh sửa file `_config.butterfly.yml` trong thư mục theme `butterfly`.

7. **Build và khởi động server**:
   Sau khi đã hoàn tất cấu hình, bạn có thể build và khởi động server để xem kết quả.

   ```bash
   hexo clean
   hexo generate
   hexo server
   ```

   Mở trình duyệt và truy cập `http://localhost:4000` để xem blog của bạn với theme Butterfly.

### Lưu ý

- Đảm bảo rằng bạn đã cài đặt đúng phiên bản của Node.js và npm theo yêu cầu của Hexo và theme Butterfly.
- Đọc kỹ tài liệu hướng dẫn của theme Butterfly trên GitHub để biết thêm chi tiết về các cấu hình và tùy chọn nâng cao: [Hexo Theme Butterfly Documentation](https://butterfly.js.org/).

Nếu bạn gặp bất kỳ lỗi nào trong quá trình cài đặt, vui lòng cung cấp thông tin chi tiết để mình có thể hỗ trợ bạn tốt hơn.

Để cài đặt Node.js và npm, bạn cần làm theo các bước dưới đây, tùy thuộc vào hệ điều hành bạn đang sử dụng.

### Trên Windows:

1. **Tải xuống Node.js**:
   Truy cập trang [Node.js official website](https://nodejs.org/) và tải về phiên bản LTS (Long Term Support).

2. **Cài đặt Node.js**:
   Chạy file cài đặt bạn vừa tải về và làm theo các bước hướng dẫn. Chọn tùy chọn cài đặt npm cùng với Node.js.

3. **Kiểm tra cài đặt**:
   Sau khi cài đặt xong, mở Command Prompt và kiểm tra phiên bản của Node.js và npm để đảm bảo chúng đã được cài đặt đúng cách.

   ```bash
   node -v
   npm -v
   ```

### Trên macOS:

1. **Sử dụng Homebrew**:
   Nếu bạn chưa cài đặt Homebrew, hãy cài đặt nó bằng lệnh sau:

   ```bash
   /bin/bash -c "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/HEAD/install.sh)"
   ```

2. **Cài đặt Node.js**:
   Sử dụng Homebrew để cài đặt Node.js (bao gồm npm):

   ```bash
   brew install node
   ```

3. **Kiểm tra cài đặt**:
   Sau khi cài đặt xong, mở Terminal và kiểm tra phiên bản của Node.js và npm.

   ```bash
   node -v
   npm -v
   ```

### Trên Linux:

1. **Sử dụng NodeSource**:
   Thêm NodeSource repository và cài đặt Node.js. Đầu tiên, bạn cần thêm repository:

   ```bash
   curl -fsSL https://deb.nodesource.com/setup_lts.x | sudo -E bash -
   ```

2. **Cài đặt Node.js**:
   Sau khi thêm repository, bạn có thể cài đặt Node.js:

   ```bash
   sudo apt-get install -y nodejs
   ```

3. **Kiểm tra cài đặt**:
   Kiểm tra phiên bản của Node.js và npm.

   ```bash
   node -v
   npm -v
   ```

### Kiểm tra cài đặt:

Để chắc chắn rằng Node.js và npm đã được cài đặt thành công, bạn có thể kiểm tra phiên bản của chúng bằng các lệnh sau:

```bash
node -v
npm -v
```

Kết quả sẽ hiển thị phiên bản hiện tại của Node.js và npm, ví dụ:

```bash
v14.17.0
6.14.13
```

Bây giờ, bạn đã sẵn sàng để tiếp tục cài đặt và sử dụng Hexo và theme Butterfly như đã hướng dẫn trước đó.

https://github.com/project-sekai-ctf/sekai.team

https://sekai.team/

https://github.com/timlrx/tailwind-nextjs-starter-blog

# Cài đặt Vim thuần bằng tay
Mặc định, thư mục `~/.vim` sẽ không có cấu trúc để cài Plugin, chúng ta sẽ tạo các thư mục bằng cách
```bash
$ mkdir -p ~/.vim/pack/vendor/start
```
Sau đó thêm các plugin muốn cài vào thư mục đó, nó sẽ load tự động khi mở vim lên.

Ví dụ khi cài NERDTree ( Sidebar chọn file cho Vim ), ta thực hiện:
```bash
$ git clone --depth 1 \
  https://github.com/preservim/nerdtree.git \
  ~/.vim/pack/vendor/start/nerdtree
```
Nó có nghĩa là: clone plugin vào thư mục '~/.vim/pack/vendor/start/' với tên 'nerdtree'

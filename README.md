# PLSQL Fundamental Course

> This is the source code for examples in PL/SQL Fundamental course.

## Tạo kho dự án github

* Đăng nhập bằng tài khoản github (nếu chưa có, bạn có thể tạo một tài khoản github mới)
* Tạo kho mã nguồn (New Repository)
* Ghi nhớ đường dẫn tới kho mã nguồn (ví dụ: `https://github.com/pnhung177/plsql-fundamental.git`) để ánh xạ vào thư mục mã nguồn dự án.

## Tạo thư mục dự án git

Để tạo một dự án git từ đầu, chúng ta thực hiện theo các bước sau:

#### Tạo thư mục chứa dự án

```
$ mkdir plsql-fundamental
```

#### Chuyển vào trong thư mục

```
$ cd plsql-fundamental
```

#### Khởi tạo kho git cục bộ

```
$ git git
```

#### Ánh xạ thư mục với kho mã nguồn

```
$ git remote add origin https://github.com/pnhung177/plsql-fundamental.git
```

## Clone kho mã nguồn về máy

Trong trường hợp bạn đã có sẵn kho mã nguồn trên github rồi, vì lý do nào đó bạn chuyển sang máy tính mới (chẳng hạn khi về nhà dùng máy tính ở nhà, mà máy này thì chưa có dự án) và bạn muốn "kéo" toàn bộ dự án đang làm việc về máy tín mới. Cách làm như sau:

Chọn một thư mục chứa thư mục dự án. Thường thì một số người có thói quen lưu tất cả các dự án vào thư mục `Projects` hoặc `Workspace` để tiện quản lý. Giả sử bạn muốn để dự án này vào thư mục Projects bên trong thư mục riêng. 

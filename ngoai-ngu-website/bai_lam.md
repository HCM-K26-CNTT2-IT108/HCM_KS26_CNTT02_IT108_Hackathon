# BÀI LÀM – HACKATHON 01

- **Mã đề:** 13
- **Họ tên:** HÀ GIA BÁCH
- **Lớp:** CNTT2
- **Link repository** :https://github.com/HCM-K26-CNTT2-IT108/HCM_KS26_CNTT02_IT108_Hackathon.git
- **Hệ điều hành (Windows/macOS):** WINDOW

## 4.2. Thao tác máy tính cơ bản bằng CLI

### Các lệnh đã chạy

```shell
 pwd
  ls -force
 move-item  .\Thoi_Khoa_Bieu.txt .\docs\
 move-item .\Logo_Trung_Tam_Ngoai_Ngu.PNG .\media\
 rm -r .\temp_213.tmp
  cd .\logs\
  ls
  cd ..

```

### Kết quả liệt kê toàn bộ dự án (Windows: Get-ChildItem -Recurse -Force; macOS: ls -aR)

```text
Windows PowerShell
Copyright (C) Microsoft Corporation. All rights reserved.

PS D:\BAI_KIEM_TRA\starter-kit\ngoai-ngu-website> pwd

Path
----
D:\BAI_KIEM_TRA\starter-kit\ngoai-ngu-website


PS D:\BAI_KIEM_TRA\starter-kit\ngoai-ngu-website> ls -force


    Directory: D:\BAI_KIEM_TRA\starter-kit\ngoai-ngu-website


Mode                 LastWriteTime         Length Name
----                 -------------         ------ ----
d-----        10/28/2026   1:46 PM                backup
d-----        10/28/2026   1:49 PM                data
d-----        10/28/2026   1:45 PM                docs
d-----        10/28/2026   1:49 PM                logs
d-----        10/28/2026   1:45 PM                media
d-----        10/28/2026   1:48 PM                Ngoai Ngu
                                                  Website FINAL
-a----        10/27/2026   1:31 AM             68 .env
------        10/27/2026   1:31 AM           2227 bai_lam.md
-a----        10/27/2026   1:31 AM           4365 Logo_Trung_Tam_
                                                  Ngoai_Ngu.PNG
-a----        10/27/2026   1:31 AM             67 Thoi_Khoa_Bieu.
                                                  txt


PS D:\BAI_KIEM_TRA\starter-kit\ngoai-ngu-website> --help
At line:1 char:3
+ --help
+   ~
Missing expression after unary operator '--'.
At line:1 char:3
+ --help
+   ~~~~
Unexpected token 'help' in expression or statement.
    + CategoryInfo          : ParserError: (:) [], ParentContain
   sErrorRecordException
    + FullyQualifiedErrorId : MissingExpressionAfterOperator

PS D:\BAI_KIEM_TRA\starter-kit\ngoai-ngu-website> move-item  -itemtype file -name .\Thoi_Khoa_Bieu.txt .\docs
Move-Item : A parameter cannot be found that matches parameter
name 'itemtype'.
At line:1 char:12
+ move-item  -itemtype file -name .\Thoi_Khoa_Bieu.txt .\docs
+            ~~~~~~~~~
    + CategoryInfo          : InvalidArgument: (:) [Move-Item],
   ParameterBindingException
    + FullyQualifiedErrorId : NamedParameterNotFound,Microsoft.P
   owerShell.Commands.MoveItemCommand

PS D:\BAI_KIEM_TRA\starter-kit\ngoai-ngu-website> move-item  .\Thoi_Khoa_Bieu.txt .\docs\
PS D:\BAI_KIEM_TRA\starter-kit\ngoai-ngu-website> move-item .\Logo_Trung_Tam_Ngoai_Ngu.PNG .\media\
PS D:\BAI_KIEM_TRA\starter-kit\ngoai-ngu-website> cd .\media\
PS D:\BAI_KIEM_TRA\starter-kit\ngoai-ngu-website\media> cp .\Logo_Trung_Tam_Ngoai_Ngu.PNG
cp : Cannot overwrite the item D:\BAI_KIEM_TRA\starter-kit\ngoai-
ngu-website\media\Logo_Trung_Tam_Ngoai_Ngu.PNG with itself.
At line:1 char:1
+ cp .\Logo_Trung_Tam_Ngoai_Ngu.PNG
+ ~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~
    + CategoryInfo          : WriteError: (D:\BAI_KIEM_TRA...m_N
   goai_Ngu.PNG:String) [Copy-Item], IOException
    + FullyQualifiedErrorId : CopyError,Microsoft.PowerShell.Com
   mands.CopyItemCommand

PS D:\BAI_KIEM_TRA\starter-kit\ngoai-ngu-website\media> cp --help 
cp : Cannot find path
'D:\BAI_KIEM_TRA\starter-kit\ngoai-ngu-website\media\--help'
because it does not exist.
At line:1 char:1
+ cp --help
+ ~~~~~~~~~
    + CategoryInfo          : ObjectNotFound: (D:\BAI_KIEM_TRA..
   .te\media\--help:String) [Copy-Item], ItemNotFoundException
    + FullyQualifiedErrorId : PathNotFound,Microsoft.PowerShell.
   Commands.CopyItemCommand

PS D:\BAI_KIEM_TRA\starter-kit\ngoai-ngu-website\media> cp-help
cp-help : The term 'cp-help' is not recognized as the name of a
cmdlet, function, script file, or operable program. Check the
spelling of the name, or if a path was included, verify that the
path is correct and try again.
At line:1 char:1
+ cp-help
+ ~~~~~~~
    + CategoryInfo          : ObjectNotFound: (cp-help:String) [
   ], CommandNotFoundException
    + FullyQualifiedErrorId : CommandNotFoundException

PS D:\BAI_KIEM_TRA\starter-kit\ngoai-ngu-website\media> cp--help
cp--help : The term 'cp--help' is not recognized as the name of
a cmdlet, function, script file, or operable program. Check the
spelling of the name, or if a path was included, verify that the
path is correct and try again.
At line:1 char:1
+ cp--help
+ ~~~~~~~~
    + CategoryInfo          : ObjectNotFound: (cp--help:String)
   [], CommandNotFoundException
    + FullyQualifiedErrorId : CommandNotFoundException

PS D:\BAI_KIEM_TRA\starter-kit\ngoai-ngu-website\media> cd ..
PS D:\BAI_KIEM_TRA\starter-kit\ngoai-ngu-website> cd '.\Ngoai Ngu Website FINAL\'
PS D:\BAI_KIEM_TRA\starter-kit\ngoai-ngu-website\Ngoai Ngu Website FINAL> cd ..
PS D:\BAI_KIEM_TRA\starter-kit\ngoai-ngu-website> rm -r .\temp_213.tmp
PS D:\BAI_KIEM_TRA\starter-kit\ngoai-ngu-website> cd .\logs\
PS D:\BAI_KIEM_TRA\starter-kit\ngoai-ngu-website\logs> ls


    Directory: D:\BAI_KIEM_TRA\starter-kit\ngoai-ngu-website\logs


Mode                 LastWriteTime         Length Name
----                 -------------         ------ ----
-a----        10/27/2026   1:31 AM           1117 Course.log


PS D:\BAI_KIEM_TRA\starter-kit\ngoai-ngu-website\logs> cd ..
PS D:\BAI_KIEM_TRA\starter-kit\ngoai-ngu-website>

```


```

## 4.3. Lọc log thủ công

### Lệnh đã chạy

```shell
ni daily_report.txt ; get-content .\Course.log | select-string "ERROR" > .\daily_report.txt

```

### 2 dòng lỗi đầu tiên trong daily_report.txt

```text
2 0 2 6 - 0 3 - 2 8   0 8 : 2 4 : 2 8   [ E R R O R ]   H e t   t h o i   g i a n   c h o   ( t i m e o u t ) 
 
 2 0 2 6 - 0 3 - 2 8   0 8 : 3 0 : 2 8   [ E R R O R ]   H e t   t h o i   g i a n   c h o   ( t i m e o u t ) 

```

## 4.4. Thao tác với tài liệu Markdown (README.md)

> README.md được chấm trực tiếp trên file `README.md` ở gốc dự án. Đánh dấu `[x]` vào các mục đã làm để tự kiểm tra.

- [ ] Heading 1: tên dự án
- [ ] Mô tả ngắn có cả **in đậm** và *in nghiêng*
- [ ] Bảng `Thư mục | Nội dung`, ít nhất 3 dòng dữ liệu
- [ ] Code block chứa lệnh PowerShell/Terminal liệt kê nội dung dự án
- [ ] Task list ít nhất 2 công việc, có ít nhất 1 mục đã hoàn thành
- [ ] Blockquote nhắc không upload `.env`

## 4.5. Chạy script auto_report (.ps1 hoặc .sh)

### Lệnh chạy (Windows: nếu dùng Phụ lục 2 thì ghi cả 2 lệnh)

```shell
# Ghi lệnh vào đây (xoá dòng này)

```

### Kết quả hiển thị

```text
(Dán kết quả vào đây – xoá dòng này)

```

## 4.6. Đếm số dòng lỗi

### Lệnh

```shell
# Ghi lệnh vào đây (xoá dòng này)

```

### Kết quả đếm (Windows: giá trị Count; macOS: con số in ra)

```text
(Dán kết quả vào đây – xoá dòng này)

```

## 4.7. Báo cáo tổng hợp

### Các lệnh đã chạy

```shell
# Ghi lần lượt các lệnh đã chạy, mỗi lệnh một dòng (xoá dòng này)

```

### Nội dung file logs/tong_hop.txt

```text
(Dán kết quả vào đây – xoá dòng này)

```

## 4.8. Excel

> Phần Excel được chấm trực tiếp trên file `data/dang_ky_hoc_thang_3.xlsx`, không cần ghi vào đây.

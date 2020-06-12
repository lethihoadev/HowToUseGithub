
# Tạo reposity
Tạo folder (HowToUseGithub) ->cd đến folder đã tạo

## Kết nối:
B1: Mở folder đã tạo (dùng sublime)
B2: git init
B3: git memote add origin (origin như một đường link, có thể thay đổi bằng tên khác)
B4: git remove -v (kiểm tra xem câu lệnh đã đúng hay chưa)

## Đẩy Code:
B1: Tạo file bất kỳ (index.html, index.js)
B2: git add --all (thêm, đẩy tất cả các file đã tạo trong folder (HowToUseGithub))
B3: git status (iểm tra lại đã thêm được hay chưa)
B4: git commit -m "Add index.html file" ( đẩy file với nội dung "Add index.html file")
B5: git log (Kiểm tra xem đã đẩy thành công hay chưa)
B6: gitk (giao diện thông báo xuất hiện, xem chi tiết hơn các file đã tạo và những nội dung đã thay đổi)

## Đẩy Code lên Github:
get push origin master (đẩy lên nhánh master đã tạo ban đầu)

## Xóa file và quay cho file trở lại
B1: gitk (giao diện thông báo xuất hiện)
B2: chọn file muốn xóa (tại SHA1 ID:76876879879880o09)
B3: git reset --hard "<"commit id">" (của file muốn xóa)

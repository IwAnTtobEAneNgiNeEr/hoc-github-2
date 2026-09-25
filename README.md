CLONE
clone <url>

VÀO REPO
cd <repo>

TẠO BRANCH
switch -c <name>

TẠO FILE
echo Ten: <name> > members\<name>.txt
( cái này là đặt tên file, nhớ có dấu > ) -- mà khỏi tạo cũng dc
mở trực tiếp kiểu notepad text.md  để mở file trong notepad ( sau này có thể là app khác vd code <tên file> . là mở vscode )

XEM FILE
type members\<name>.txt
( check ndung bên trong ) 

LƯU THAY ĐỔI
add .
status
commit -m "add <name>"
git add . xong thì chạy:

status

Nếu file thay đổi đã được đưa vào vùng staged và hiện ở mục Changes to be committed (thường màu xanh lá) thì OK.

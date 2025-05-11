git init 
git add <>
git commit "message for commit to local repository"

git log --oneline ตรวจสอบ version. ที่มีการ conmit
git log --graph ดูว่าใครแก้ไขอะไรเมื่อไหร่ ? 

git diff <commit_id>
git diff <commit_id> <commit_id> ตรวจสอบ version ของสอง commit id

git checkout <file-name> 

git reset "file_name" ยกเลิกหรือ ย้อนกลับไปยัง stage ที่ยังไม่ commit ใน local repository. 
git reset --option <commit_id>  การย้อนคืน Version. 
  option 
     git reset --hard f8ff1eb คืนไปยังเวอร์ชั่นที่ระบุ commit_id และทำลายไฟล์ที่อยู่ใน Commit เหล่านั้น.
     git reset --soft ลบ commit ทั้งหมดที่อยู่หลัง commit_id และนำไฟล์ที่อยู่ใน commit นั้นกลับมายัง Staging Area.
     git reset --mixed ลบ commit ทั้งหมดที่อยู่หลัง commit_id และนำไฟล์ที่อยู่ใน commit นั้นกลับมายัง Working Directory. 
git branch 

git rebase 

git branching
    git branch การแสดงชื่อ branch.
    git checkout -b <ชื่อ branch> การสลับและสร้าง branch ให้เว้นวรรค.
    git branch -d <ชื่อ branch> ลบ branch.
    git merge <ชื่อ branch> รวม branch.
    git checkout master  สลับไปยัง branch หลัก. 

git merge add-syncmasterdata  'merge master branch กับกิ่ง add-syncmasterdata เข้าด้วยกัน.

การ update code to github.  โดยใช้ git push 

git branch -M main
git remote add origin https://github.com/AekpongSS/testGitHub.git
git push -u origin main
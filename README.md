# Web Semantic Lab 
โปรเจคนี้เป็นส่วนหนึ่งของวิชา Web Frontend Development 

## รายละเอียด 
- การใช้ Semantic HTML 
- Form Validation 
- ARIA Labels 

## git command used in this lab 
git config --global user.name "Supakan06"
git config --global user.email "66160033@go.buu.ac.th"
git clone https://github.com/Supakan06/web-semantic-lab
git add README.md
git commit -m "comment โปรเจคเเละรายละเอียด"  
git push
git checkout -b development
git add . 
git commit -m "สร้างโครงสร้างโปรเจคเริ่มต้น"

git checkout -b feature/homepage                  
git add index.html contact.html 
git commit -m "สร้างโครงสร้างเริ่มต้นของโปรเจค"
git add index.html
git commit -m "เพิ่ม header และ nav ในหน้าหลัก"
git add index.html
git commit -m "เพิ่มส่วน main และ article ในหน้าหลัก"
git add index.html  
git commit -m  "เพิ่ม aside และ footer ในหน้าหลัก"

git checkout -b feature/contact
git add contact.html
git commit -m "สร้างโครงสร้างพื้นฐานหน้าติดต่อ"
git add contact.html
git commit -m "เพิ่มฟอร์มพื้นฐานในหน้าติดต่อ"   
git add contact.html   
git commit -m "เพิ่ม validation ในฟอร์มติดต่อ" 
git add contact.html   
git commit -m "เพิ่ม ARIA labels ในฟอร์ม" 
git add contact.html   
git commit -m "เพิ่ม ARIA landmarks ในการนําทาง"
git add index.html  
git commit -m "เเก้ไข index หลังCheck W3C Validator "
git add contact.html   
git commit -m "เเก้ไข contact หลังCheck W3C Validator "

git checkout development
git add README.md
git commit -m "รวบรวมคำสั่ง git ทั้งหมด"
git merge feature/homepage
git merge feature/contact
git push origin development

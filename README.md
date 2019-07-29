# การบ้านครั้งที่1

ให้นักเรียนสรุปคำสั่ง cli ที่เรียนมาด้วย linux

# Run your Ubuntu Update
คำส่ง | การใช้งาน
-----|---------
sudo apt update | อัพเดทหลักฐานข้อมูลของแพ็คเกจทั้งหมด
sudo apt upgrade | เช็คดูว่าแพ็กเก็จที่ติดตั้งไปทั้งหมดมีเพ็กเก็จใดมีการอัพเดทบ้าง ต่อจากนั้นก็จะถามว่าต้องการดาวน์โหลดและติดตั้งหรือไม่
sudo apt dist -upgrade | อัพเกรดทั้งหมดเป็นเวอร์ชั่นล่าสุดในที่เก็บสำหรับUbuntu
sudo do-release-upgrade | อัพเกรดเป็นเวอร์ชั่น/รีลีสใหม่ของUbuntu
sudo do-release-upgrade | บังคับให้อัปเกรดจาก Ubuntu 16.04 LTS เป็น Ubuntu 18.04 LTS

# Requirement
คำส่ง | การใช้งาน
-----|---------
sudo apt install tree | ติดตั้งแพ็คเกจแบบต้นไม้

# Working Directory
คำส่ง | การใช้งาน
-----|---------
tree | แสดงรายการไฟล์และโฟล์เดอร์ในรูปแบบของต้นไม้
pwd | แสดงตำแหน่งโฟล์เดอร์ที่ทำงานอยู่
cd | คำสั่งเปลี่ยนโฟล์เดอร์ทำงาน
ls | คำสั่งแสดงรายการไฟล์

# Files and Folders
คำส่ง | การใช้งาน
-----|---------
cp | copy ข้อมูล
mv | ย้ายตำแหน่ง file หรือ directory
rm | ลบ file หรือ directory
mkdir | สร้าง directory
chmod | เปลี่ยนสิทธิ์ในการเข้าถึง file
chown | เปลี่ยนเจ้าของ file หรือ directory

# System Information
คำส่ง | การใช้งาน
-----|---------
df | แสดงข้อมูลพื้นที่ disk ทั้งหมด
free | แสดงข้อมูลการใช้งาน memory
uname | แสดงชื่อระบบของ server
ps | แสดง process ที่ทำงานใน server
top | จัดเรียงอันดับแสดงการทำงานของ process
ifconfig | แสดงข้อมูลและเปลี่ยนค่า interface server

# Text Files
คำส่ง | การใช้งาน
-----|---------
find | ใช้ในการค้นหา file หรือ directory
grep | ค้นหาบรรทัดใน file ที่ตรงเงื่อนไข
sed | เปลี่ยนแปลงข้อมูล text ที่มีรูปแบบซบซ้อน
nano | สร้างหรือแก้ไข file ข้อมูล text
cat | แสดงข้อมูลภายใน file ในรูปแบบ text
less | อ่านข้อมูลและค้นหาข้อมูลใน file
more | อ่านข้อมูลและค้นหาข้อมูลใน file

# Users Managment
คำส่ง | การใช้งาน
-----|---------
who | แสดงข้อมูล user ที่ login ขณะนั้น
whoami | แสดงชื่อ user ที่ใช้ login
groups | แสดงข้อมูล group ของ system user
adduser | ใช้เพิ่มหรือเปลี่ยนแปลง user บน linux
deluser | ใช้ในการลบ user ออกจากระบบ
passwd | เปลี่ยน password ของ system user
addgroup | เพิ่มรายชื่อกลุ่มของ user
delgroup | ลบรายชื่อกลุ่มของ user
man | แสดงคู่มือการใช้งาน program

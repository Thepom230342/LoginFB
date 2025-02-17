# คู่มือการลบข้อมูลใน Meta Developer Facebook

## การลบข้อมูลแอปพลิเคชัน

1. เข้าสู่ระบบที่ [Meta for Developers](https://developers.facebook.com/)
2. ไปที่แผงควบคุม (Dashboard)
3. เลือกแอปพลิเคชันที่ต้องการลบข้อมูล

### ขั้นตอนการลบข้อมูล

#### 1. การลบข้อมูลผู้ใช้
- เข้าไปที่เมนู "App Review" > "My Permissions and Features"
- เลือก "Remove" ที่สิทธิ์การเข้าถึงที่ต้องการลบ
- ยืนยันการลบสิทธิ์การเข้าถึง

#### 2. การลบ Test Users
- ไปที่เมนู "Roles" > "Test Users"
- เลือกผู้ใช้ทดสอบที่ต้องการลบ
- คลิกที่ปุ่ม "Delete"

#### 3. การลบ Access Tokens
- ไปที่เมนู "Tools" > "Graph API Explorer"
- ลบ Access Tokens ที่ไม่ได้ใช้งานแล้ว

#### 4. การลบแอปพลิเคชันทั้งหมด
1. ไปที่การตั้งค่าแอป (App Settings)
2. เลื่อนลงไปด้านล่างสุด
3. คลิกที่ "Delete App"
4. ยืนยันการลบแอปพลิเคชัน

## ข้อควรระวัง
- การลบข้อมูลไม่สามารถเรียกคืนได้
- ควรสำรองข้อมูลสำคัญก่อนทำการลบ
- ตรวจสอบให้แน่ใจว่าไม่มีการใช้งาน API หรือบริการที่เกี่ยวข้องก่อนลบ

## การสนับสนุน
หากพบปัญหาในการลบข้อมูล สามารถติดต่อ:
- [Meta Developer Support](https://developers.facebook.com/support/)
- [Meta Developer Community](https://developers.facebook.com/community/)

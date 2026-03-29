# LogiTrack Delivery & Receipt System (Secure Edition)

ระบบจัดการติดตามพัสดุและระบบเซ็นรับสินค้าออนไลน์ฉบับสมบูรณ์ (Production Ready) ที่ได้รับการปรับปรุงความปลอดภัยด้านต่างๆ เช่น การจัดการขยะไฟล์รูปภาพ, การป้องกัน Brute Force, การจำกัดสิทธิ์ในโฟลเดอร์อัปโหลด, และการปกปิดข้อมูลส่วนบุคคลตามหลัก Privacy

## Features
- Secure PDO Prepared Statements for complete SQL Injection prevention
- CSRF Token validation on all state-changing requests
- Strict XSS protection with h() wrapper and Content-Type validation
- Rate Limiting & Anti-Brute Force mechanism on Login page
- File Unlink implementation to prevent storage accumulation of unused images
- Privacy Phone Masking for public tracking system
- Enforced Signature & Proof requirements before completing delivery status
- Strong Password Policy implementation
- Centralized Flash Message system for better UX instead of die()
- .htaccess protection for the uploads directory to prevent execution and directory listing
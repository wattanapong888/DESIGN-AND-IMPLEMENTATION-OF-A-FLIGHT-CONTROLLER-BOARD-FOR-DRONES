# DESIGN-AND-IMPLEMENTATION-OF-A-FLIGHT-CONTROLLER-BOARD-FOR-DRONES

  โครงงานนี ้มีวัตถุประสงค์เพื ่อพัฒนาโดรนแบบควอดคอปเตอร์ที ่ใช้ไมโครคอนโทรลเลอร์ STM32 เป็น
หน่วยประมวลผลหลักร่วมกับเซนเซอร์ตรวจวัดการเคลื ่อนที ่ MPU-6050 ซึ ่งประกอบด้วย Accelerometer และ 
Gyroscope เพื ่อใช้ในการตรวจวัดการเอียงและการหมุนของโดรนแบบเรียลไทม์ โดยได้ออกแบบและสร้าง
แผงวงจรควบคุม (PCB) ขึ้นเอง เพื่อให้ระบบมีความเหมาะสมกับโครงสร้างโดรนและลดการใช้สายเชื ่อมต่อภายใน 
ตัวโดรนควบคุมการทรงตัวด้วยอัลกอริทึม PID พร้อมสื่อสารกับรีโมตไร้สายในการควบคุมทิศทางการบิน 

  The objective of this project is to develop a quadcopter drone utilizing the STM32 
microcontroller as the main processing unit, integrated with the MPU-6050 motion sensor 
consisting of an accelerometer and gyroscope for real-time detection of the drone's inclination 
and rotational movement. A custom-designed Printed Circuit Board (PCB) is implemented to 
optimize system integration with the drone structure and to minimize internal wiring. The drone’s 
stability is controlled using a PID control algorithm, while wireless communication is employed 
for directional control during flight.

# Ragnarok Online ClientSide : XRay Clients

> Credits: Meruru & Pinky for releasing Xray client.
> 
> Guide: ไม่สามารถหาไกด์มาแปลให้ได้จริง ๆ แต่ถ้าอารมณ์ดี มีเวลา จะนั่งทำไกด์ส่วนนี้ให้ ( ไม่ต้องรออย่างมีความหวัง )

#### ปี 2007
- kROsakexe0423aO[Xray] - O = Use OLD Login Background. [PACKETVER 7]
- kROsakexe0423aN[Xray] - N = Use NEW Login Background. [PACKETVER 7]
- kROsakexe0904aO[Xray] - O = Use OLD Login Background. [PACKETVER 7]
- kROsakexe0904aN[Xray] - N = Use NEW Login Background. [PACKETVER 7]

#### ปี 2008
- kROsakexe0102aO[Xray] - O = Use OLD Login Background. [PACKETVER 9]
- kROsakexe0102aN[Xray] - N = Use NEW Login Background. [PACKETVER 9]
- kROsakexe0528aO[Xray] - O = Use OLD Login Background. [PACKETVER 9]
- kROsakexe0528aN[Xray] - N = Use NEW Login Background. [PACKETVER 9]
- kROsakexe0528aOv2[9 slots][Xray] - O = Use OLD Login Background. [PACKETVER 9]
- kROsakexe0528aNv2[9 slots][Xray] - N = Use OLD Login Background. [PACKETVER 9]
- kROsakexe0528aOv2[12 slots][Xray] - O = Use NEW Login Background. [PACKETVER 9]
- kROsakexe0528aNv2[12 slots][Xray] - N = Use NEW Login Background. [PACKETVER 9]

#### ปี 2009
- kROsakexe0225bN[9 slots][Xray] - N = Use NEW Login Background. [PACKETVER 9][ อ่าน NOTE ]
- kROsakexe0225bN[12 slots][Xray] - N = Use NEW Login Background. [PACKETVER 9][ อ่าน NOTE2 ]
- kROragexeRE1013aN[9 slots][Xray] - N = Use NEW Login Background. [PACKETVER 9][ อ่าน NOTE3 ]
- kROragexeRE1013aN[12 slots][Xray] - N = Use NEW Login Background. [PACKETVER 9][ อ่าน NOTE3 ]


- NOTE: เป็นไคลเอ็นต์ที่ผ่านการ Hex มาไว้แล้ว
- NOTE2: สำหรับไคลเอ็นต์ปี 2008-09-10aSakexe และปีที่สูงกว่านั้น ซัพพอทกับ eA Trunk 13293+ และ Stable 14287+
- NOTE3: เบื้องต้นสำหรับใช้งาน Ragnarok RE:

#### [ ส่วนของเซิฟเวอร์ ]
- แก้ไข packet_db.txt ในโฟลเดอร์ DB โดยเปลี่ยนเลข 23 เป็น default ที่ packet_db_ver.
- สำหรับใครที่ใช้ 3CeAM ไม่จำป็นต้องแก้ใขในส่วนของ packet_db.txt

#### [ ส่วนของไคลเอ็นต์ ]
- เปลี่ยนชื่อไฟล์ sclientinfo.xml เป็น clientinfo.xml
- เพิ่ม rdata.grf เข้าไปให้ตัวไคลเอ็นต์อ่านในไฟล์ DATA.INI ( กรณีใช้ตัวเกมของเกาหลี )
- อาจจะมีการเปลี่ยนแปลงของ "lua files" หากมีการอัพเดตแพทซ์ของเซิฟเวอร์หลักโปรดระวังในส่วนนี้
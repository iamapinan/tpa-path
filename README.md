# ยินดีต้อนรับสู่ Thai Programmer Career Paths 
แนวทางแนะนำสำหรับเส้นทางการเติบโตสำหรับโปรแกรมเมอร์ (Programmer Career Paths) ในประเทศไทยนะครับ

## เข้าเยี่ยมชม Thai Programmer Career Paths Website
https://roadmap.thaiprogrammer.org/

## VitePress คืออะไร?
`VitePress` เป็นเครื่องมือสร้างเว็บไซต์แบบ Static Site Generator (SSG) ที่ออกแบบมาเพื่อสร้างเว็บไซต์ที่รวดเร็วและเน้นเนื้อหา โดย VitePress จะนำเนื้อหาที่เขียนในรูปแบบ Markdown มาปรับใช้กับธีมแล้วสร้างหน้า HTML แบบ static ที่สามารถเผยแพร่ได้ง่าย

## ได้บันดาลใจในการใช้ VitePress มาจากไหน
ประทับใจ VitePress หลังจากที่ได้ชม [Video สร้างเว็บแหล่งความรู้สวยๆ ด้วย VitePress โดยคุณ Thai Pangsakulyanont](https://www.youtube.com/watch?v=szr7swXqPSw)
ขอบคุณเนื้อหาดีๆมากๆนะครับ 
รวมถึงขอบคุณทาง [Creatorsgarten](https://www.youtube.com/@creatorsgarten) ที่จัดงาน [Event: BKK.JS #19](https://creatorsgarten.org/event/bkkjs19) แบ่งปันความรู้ดีๆขึ้นครับผม

## เริ่มต้น VitePress ยังไง
### แหล่งอ้างอิง
- [Getting Started](https://vitepress.dev/guide/getting-started)

### สิ่งที่ต้องมีก่อนติดตั้ง VitePress
- [Node.js](https://nodejs.org/) version 18 or higher.
- Terminal for accessing VitePress via its command line interface (CLI).
- Text Editor with [Markdown](https://en.wikipedia.org/wiki/Markdown) syntax support.
   - [VSCode](https://code.visualstudio.com/) is recommended, along with the [official Vue extension](https://marketplace.visualstudio.com/items?itemName=Vue.volar).

### ติดตั้ง VitePress กันเถอะ
```bash
npm add -D vitepress
```

### พร้อมรัน VitePress ล้าวววว
```bash
npm run docs:dev
```

ถ้ารันขึ้นแล้วให้ลองดูที่ [http://localhost:5173/](http://localhost:5173/)

## VS Code Tasks
ใน `Visual Studio Code (VS Code)` คำสั่ง `Run Tasks` คือฟีเจอร์ที่ช่วยให้เราสามารถรันงานหรือสคริปต์ที่กำหนดไว้ในไฟล์ `tasks.json` ซึ่งอยู่ในโฟลเดอร์ `.vscode` เพื่อทำการคอมไพล์โค้ด, รันทดสอบ, ทำการ linting หรือการทำงานอื่นๆ ที่จำเป็น

[tasks.json](./.vscode/tasks.json) ใน Project นี้
```json
{
  // See https://go.microsoft.com/fwlink/?LinkId=733558
  // for the documentation about the tasks.json format
  "version": "2.0.0",
  "tasks": [
    {
      "label": "Install VitePress", // ติดตั้ง VitePress กันเถอะ 
      "type": "shell",
      "command": "npm add -D vitepress"
    },
    {
      "label": "Run VitePress", // รัน VitePress กันเถอะ
      "type": "shell",
      "command": "npm run docs:dev"
    }
  ]
}
```

### วิธีรัน VS Code Tasks
1.	เปิด `Command Palette` โดยการกด `Ctrl+Shift+P` บน Windows หรือ `Cmd+Shift+P` บน macOS
2.	พิมพ์ `Tasks: Run Task` และเลือก
3.	เลือกงานที่ต้องการรันจากรายการที่ปรากฏดังนี้
   3.1. เลือก `Install VitePress` เพื่อติดตั้ง VitePress
   3.2. เลือก `Run VitePress` เพื่อรัน VitePress
4. ถ้ารันขึ้นแล้วให้ลองดูที่ [http://localhost:5173/](http://localhost:5173/)

![](./images/vscodetasks.jpg)

## ขอบคุณผู้ร่วมพัฒนาทุกคน ❤

 <a href = "https://contrib.rocks/image?repo=ThaiProgrammer/tpa-path">
   <img src = "https://contrib.rocks/image?repo=ThaiProgrammer/tpa-path"/>
 </a>

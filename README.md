- 👋 Hi, I’m @GGuy001
- 👀 I’m interested in ...
- 🌱 I’m currently learning ...
- 💞️ I’m looking to collaborate on ...
- 📫 How to reach me ...

<!---
GGuy001/GGuy001 is a ✨ special ✨ repository because its `README.md` (this file) appears on your GitHub profile.
You can click the Preview link to take a look at your changes.
--->

#ระเบียบเป็นสิ่งสำคัญ รูปแบบการจับคู่ LAST มีลำดับความสำคัญสูงสุด
มีการใช้รูปแบบสไตล์ gitignore #รูปแบบ ไม่ใช่ globs
# https://docs.github.com/articles/about-codeowners
# https://git-scm.com/docs/gitignore

#วิศวกรรมศาสตร์
* .js  @ github/docs-engineering
* .ts  @ github/docs-engineering
* .tsx  @ github/docs-engineering
/ .github / @ github/docs-engineering
/ script / @ github/docs-engineering
/ รวม / @ github/docs-engineering
app.json  @ github/docs-engineering
Dockerfile  @ github/docs-engineering
package-lock.json  @ github/docs-engineering
package.json  @ github/docs-engineering

#โลคัลไลเซชัน
/ .github / เวิร์กโฟลว์ / crowdin.yml  @ github/docs-localization
/ crowdin * .yml  @ github/docs-engineering  @ github/docs-localization
/ การแปล / @ github/docs-engineering  @ github/docs-localization  @ github-actions

#นโยบายเว็บไซต์
/ เนื้อหา / github / site-policy / @ github/site-policy-admins

#กลยุทธ์เนื้อหา
/ สนับสนุน / content-markup-reference.md  @ github/docs-content-strategy
/ การสนับสนุน / content-style-guide.md  @ github/docs-content-strategy
/ สนับสนุน / content-model.md  @ github/docs-content-strategy
/ การสนับสนุน / content-style-guide.md  @ github/docs-content-strategy
/ สนับสนุน / content-templates.md  @ github/docs-content-strategy

#ตรวจสอบให้แน่ใจว่าผู้ดูแล Octokit ได้รับแจ้งเกี่ยวกับการเปลี่ยนแปลง
# ที่เกี่ยวข้องกับห้องสมุด Octokit (https://github.com/octokit)
/ เนื้อหา / ส่วนที่เหลือ / อ้างอิง @ github/octokit-maintainers
© 2021 GitHub, Inc.

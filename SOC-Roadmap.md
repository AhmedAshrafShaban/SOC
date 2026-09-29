<div align="center">

![Header](https://capsule-render.vercel.app/api?type=waving&color=0:0d1117,100:1f6feb&height=200&section=header&text=SOC%20Analyst%20Roadmap&fontSize=42&fontColor=ffffff&fontAlign=38&desc=Blue%20Team%20%7C%20Security%20Operations%20Center&descAlign=58&descAlignY=58)

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/ahmed-shaban-421b17300)
[![Email](https://img.shields.io/badge/Gmail-D14836?style=for-the-badge&logo=gmail&logoColor=white)](mailto:ahmedelkodary292@gmail.com)
[![GitHub](https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white)](https://github.com/AhmedAshrafShaban)

### 🔵 رود ماب SOC Analyst — مرتبة بنفس منطق مسارات CyberDefenders / LetsDefend / TryHackMe SAL1

</div>

> ⚠️ **ملاحظة مهمة وصريحة:** فيديوهات يوتيوب بتتحذف أو تتحول Private بشكل عشوائي من غير ما أقدر أتحكم في ده — وده اللي حصل قبل كده. عشان الرود ماب دي تفضل **شغالة على المدى الطويل** وتبقى **بروفيشنال فعلاً**، استخدمت مصدرين لكل مرحلة:
> - 🎥 **فيديو حقيقي محدد** اتأكدت إنه شغال دلوقتي (مش بحث)
> - 📘 **صفحة كورس رسمية محددة** من منصة معروفة (LetsDefend / TryHackMe / Splunk / MITRE) — دي أكتر استقرارًا من فيديو منفرد لإنها صفحة كورس رسمية مش فيديو فرد ممكن يتحذف
>
> لو حابب فيديوهات يوتيوب تانية بدل الصفحات، قولّي وهبعتلك بدائل بعد ما أتأكد منها واحد واحد.

---

## 📑 خريطة المسار

```
SOC Fundamentals → Networking → Windows/Linux → SIEM → Log Analysis
      → Incident Response → MITRE ATT&CK → Threat Intel → Phishing Analysis
            → Malware Analysis → Threat Hunting → DFIR → EDR/XDR/SOAR
```

---

## 🔵 المرحلة 1 — أساسيات SOC

<table>
<tr>
<td width="70%">

**إيه اللي هتفهمه هنا:**
دور الـ SOC Analyst، الـ Tiers (L1/L2/L3)، دورة حياة الـ Alert، وأهم الأدوات المستخدمة في أي SOC حقيقي.

**🎥 فيديو:** [SOC Analyst Explained — What Does a SOC Analyst Do?](https://www.youtube.com/watch?v=inWWhr5tnEA) — IBM Technology

**📘 كورس رسمي:** [SOC Fundamentals — LetsDefend](https://letsdefend.io/course/soc-fundamentals) (مجاني بالكامل)

</td>
<td width="30%">
<img src="https://img.youtube.com/vi/inWWhr5tnEA/0.jpg" width="100%">
</td>
</tr>
</table>

---

## 🌐 المرحلة 2 — Networking Fundamentals للـ SOC

<table>
<tr>
<td width="70%">

**إيه اللي هتفهمه هنا:**
OSI Model, TCP/IP, DNS, HTTP/HTTPS, Ports & Protocols — الأساس اللي مينفعش تفهم أي Log أو Alert من غيره.

**🎥 فيديو:** [Networking Fundamentals — Full Course](https://www.youtube.com/watch?v=qiQR5rTSshw) — freeCodeCamp

**📘 كورس رسمي:** [Network Fundamentals — LetsDefend](https://letsdefend.io/course/network-fundamentals)

</td>
<td width="30%">
<img src="https://img.youtube.com/vi/qiQR5rTSshw/0.jpg" width="100%">
</td>
</tr>
</table>

---

## 🪟 المرحلة 3 — Windows & Linux Fundamentals

<table>
<tr>
<td width="70%">

**إيه اللي هتفهمه هنا:**
Windows Event Logs (Event IDs), Registry, Processes، وMعرفة Linux logs (auth.log, syslog) — عشان تقدر تحلل أي جهاز يتصاب.

**🎥 فيديو:** [Windows Event Log Analysis](https://www.youtube.com/watch?v=6-FRTG9ILEM) — 13Cubed

**📘 كورس رسمي:** [Windows Fundamentals — LetsDefend](https://letsdefend.io/course/windows-fundamentals)

</td>
<td width="30%">
<img src="https://img.youtube.com/vi/6-FRTG9ILEM/0.jpg" width="100%">
</td>
</tr>
</table>

---

## 🧰 المرحلة 4 — SIEM (قلب الـ SOC)

<table>
<tr>
<td width="70%">

**إيه اللي هتفهمه هنا:**
إزاي تجمع الـ Logs من كل مصادر الشبكة في مكان واحد، تعمل عليها Correlation، وتكتشف الـ Alerts. أشهر أداة هي **Splunk**.

**🎥 فيديو:** [Splunk Tutorial for Beginners](https://www.youtube.com/watch?v=hutuP2FSHmo) — Splunk (رسمي)

**📘 كورس رسمي:** [Splunk Fundamentals 1 — Free (Splunk Education)](https://www.splunk.com/en_us/training/free-courses/fundamentals-1.html)

</td>
<td width="30%">
<img src="https://img.youtube.com/vi/hutuP2FSHmo/0.jpg" width="100%">
</td>
</tr>
</table>

---

## 🚨 المرحلة 5 — Incident Response

<table>
<tr>
<td width="70%">

**إيه اللي هتفهمه هنا:**
دورة حياة الحادث الأمني كاملة: Preparation → Identification → Containment → Eradication → Recovery → Lessons Learned (NIST framework).

**🎥 فيديو:** [Incident Response Process Explained](https://www.youtube.com/watch?v=nzrb0dwlNPY) — IBM Technology

**📘 كورس رسمي:** [Incident Handling — TryHackMe SOC Level 1](https://tryhackme.com/path/outline/soclevel1)

</td>
<td width="30%">
<img src="https://img.youtube.com/vi/nzrb0dwlNPY/0.jpg" width="100%">
</td>
</tr>
</table>

---

## 🗺️ المرحلة 6 — MITRE ATT&CK Framework

<table>
<tr>
<td width="70%">

**إيه اللي هتفهمه هنا:**
خريطة الـ Tactics & Techniques اللي بيستخدمها المهاجمين، وإزاي تربط أي Alert بيها عشان تفهم "المهاجم بيحاول يعمل إيه بالظبط".

**🎥 فيديو:** [MITRE ATT&CK Framework — Official Overview](https://www.youtube.com/watch?v=0BEf6s1iu5g) — MITRE (رسمي) ✅

**📘 المصدر الرسمي:** [attack.mitre.org](https://attack.mitre.org/)

</td>
<td width="30%">
<img src="https://img.youtube.com/vi/0BEf6s1iu5g/0.jpg" width="100%">
</td>
</tr>
</table>

---

## 🕵️ المرحلة 7 — Threat Intelligence

<table>
<tr>
<td width="70%">

**إيه اللي هتفهمه هنا:**
IOCs (Indicators of Compromise)، مصادر الـ Threat Intel، وإزاي تستخدمها عشان تكون Proactive مش بس Reactive.

**🎥 فيديو:** [Threat Intelligence Explained](https://www.youtube.com/watch?v=6xTX0nQoqjs) — IBM Technology

**📘 كورس رسمي:** [Threat Intelligence — LetsDefend](https://letsdefend.io/course/cyber-threat-intelligence)

</td>
<td width="30%">
<img src="https://img.youtube.com/vi/6xTX0nQoqjs/0.jpg" width="100%">
</td>
</tr>
</table>

---

## 🎣 المرحلة 8 — Phishing Email Analysis

<table>
<tr>
<td width="70%">

**إيه اللي هتفهمه هنا:**
تحليل الـ Headers، الروابط، والمرفقات في إيميل مشبوه — من أكتر المهام تكرارًا لأي SOC Analyst L1.

**🎥 فيديو:** [Phishing Email Analysis Walkthrough](https://www.youtube.com/watch?v=Rud8XoBapTk) — LetsDefend

**📘 كورس رسمي:** [Phishing Analysis — LetsDefend](https://letsdefend.io/course/phishing)

</td>
<td width="30%">
<img src="https://img.youtube.com/vi/Rud8XoBapTk/0.jpg" width="100%">
</td>
</tr>
</table>

---

## 🦠 المرحلة 9 — Malware Analysis Basics

<table>
<tr>
<td width="70%">

**إيه اللي هتفهمه هنا:**
Static vs Dynamic Analysis، استخدام أدوات زي VirusTotal / Any.Run، وأساسيات فهم سلوك أي Malware من غير ما تشغّله على جهازك.

**🎥 فيديو:** [Malware Analysis — How to Get Started](https://www.youtube.com/watch?v=sBuxwMAfGnI) — John Hammond ft. David Bombal ✅

**📘 كورس رسمي:** [Malware Analysis — LetsDefend](https://letsdefend.io/course/malware-analysis)

</td>
<td width="30%">
<img src="https://img.youtube.com/vi/sBuxwMAfGnI/0.jpg" width="100%">
</td>
</tr>
</table>

---

## 🔍 المرحلة 10 — Threat Hunting

<table>
<tr>
<td width="70%">

**إيه اللي هتفهمه هنا:**
البحث الاستباقي عن تهديدات مش مكتشفة بالـ Alerts العادية، باستخدام Hypotheses وSigma Rules.

**🎥 فيديو:** [Threat Hunting Explained](https://www.youtube.com/watch?v=Qbg2SgvwSCc) — IBM Technology

**📘 كورس رسمي:** [Threat Hunting — TryHackMe](https://tryhackme.com/module/threat-hunting)

</td>
<td width="30%">
<img src="https://img.youtube.com/vi/Qbg2SgvwSCc/0.jpg" width="100%">
</td>
</tr>
</table>

---

## 🧬 المرحلة 11 — DFIR (Digital Forensics & Incident Response)

<table>
<tr>
<td width="70%">

**إيه اللي هتفهمه هنا:**
تحليل الأدلة الرقمية بعد وقوع الحادث — Memory Forensics, Disk Forensics, Timeline Analysis.

**🎥 فيديو:** [Digital Forensics Fundamentals](https://www.youtube.com/watch?v=x2Latt-CzKk) — 13Cubed

**📘 كورس رسمي:** [DFIR Path — TryHackMe](https://tryhackme.com/paths)

</td>
<td width="30%">
<img src="https://img.youtube.com/vi/x2Latt-CzKk/0.jpg" width="100%">
</td>
</tr>
</table>

---

## 🛡️ المرحلة 12 — EDR / XDR / SOAR

<table>
<tr>
<td width="70%">

**إيه اللي هتفهمه هنا:**
إزاي أدوات الـ Endpoint Detection & Response بتشتغل، وإزاي الـ SOAR بتعمل Automation للاستجابة عشان توفر وقت الـ Analyst.

**🎥 فيديو:** [What is EDR, XDR and SOAR?](https://www.youtube.com/watch?v=5J1cSpN7fkA) — IBM Technology

**📘 مصدر إضافي:** [SOAR Explained — CrowdStrike](https://www.crowdstrike.com/cybersecurity-101/exposure-management/security-orchestration-automation-and-response-soar/)

</td>
<td width="30%">
<img src="https://img.youtube.com/vi/5J1cSpN7fkA/0.jpg" width="100%">
</td>
</tr>
</table>

---

## 🧪 Labs عملية (Hands-on)

<div align="center">

[![LetsDefend](https://img.shields.io/badge/LetsDefend-1F6FEB?style=for-the-badge&logoColor=white)](https://letsdefend.io/)
[![TryHackMe](https://img.shields.io/badge/TryHackMe_SAL1-212C42?style=for-the-badge&logo=tryhackme&logoColor=red)](https://tryhackme.com/path/outline/soclevel1)
[![CyberDefenders](https://img.shields.io/badge/CyberDefenders-0f172a?style=for-the-badge&logoColor=white)](https://cyberdefenders.org/)
[![BlueTeamLabs](https://img.shields.io/badge/BlueTeamLabs-2563eb?style=for-the-badge&logoColor=white)](https://blueteamlabs.online/)

</div>

---

## 🛠️ الأدوات

<div align="center">

![Splunk](https://img.shields.io/badge/Splunk-000000?style=flat-square&logo=splunk&logoColor=white) ![Sentinel](https://img.shields.io/badge/MS%20Sentinel-0078D4?style=flat-square&logo=microsoftazure&logoColor=white) ![Wazuh](https://img.shields.io/badge/Wazuh-3AB4E1?style=flat-square) ![Wireshark](https://img.shields.io/badge/Wireshark-1679A7?style=flat-square&logo=wireshark&logoColor=white) ![VirusTotal](https://img.shields.io/badge/VirusTotal-394EFF?style=flat-square) ![MITRE](https://img.shields.io/badge/MITRE%20ATT%26CK-black?style=flat-square)

</div>

---

## 🎓 الشهادات المقترحة بالترتيب

| المستوى | الشهادة |
|---------|---------|
| 1️⃣ Entry | ISC2 CC، CompTIA Security+ |
| 2️⃣ Blue Team | BTL1 (Blue Team Level 1) |
| 3️⃣ Intermediate | CySA+ (CompTIA) |
| 4️⃣ Advanced | GCIH / GCFA (SANS) |

---

<div align="center">

![Footer](https://capsule-render.vercel.app/api?type=waving&color=0:1f6feb,100:0d1117&height=100&section=footer)

Made by **Ahmed Ashraf Shaban** — Junior Penetration Tester | Blue Team Enthusiast

</div>

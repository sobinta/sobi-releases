# Sobi Engineering — releases

Signed Windows installers and the update manifest of **Sobi Engineering**, a design assistant for electrical designers and PLC programmers (machine control cabinets per IEC 60204-1). The source code is not here.

## Download
**[Latest version](https://github.com/sobinta/sobi-releases/releases/latest)**: open the release and download `Sobi-Engineering_<version>_x64-setup.exe`. It needs Windows 10 or 11 (64-bit).

## Updates
- **Automatic check:** an installed Sobi looks for a new version when it starts, and on request under Help → Check for updates. When it finds one it asks you before it installs.
- **Signed:** every update is signed and checked against the key built into the app, so only official builds are installed.
- **What is sent:** the check asks for `latest.json` in this repository and sends no project data.
- **Switching it off:** a company switches checks off with the environment variable `SOBI_UPDATES=off`.

## Please note
- The standards data in current versions is a **synthetic placeholder** (`NOT FOR ENGINEERING USE`). Calculation methods, traces and checks are real, but table values such as current-carrying capacities are not taken from IEC standards.
- Results support the engineer; the final responsibility for a design stays with the engineer.

---

**فارسی:** این مخزن فقط فایل‌های نصب امضاشده و فایل به‌روزرسانی برنامهٔ Sobi Engineering را دارد، نه کد برنامه را. برای نصب، [آخرین نسخه](https://github.com/sobinta/sobi-releases/releases/latest) را دانلود کنید. برنامه هنگام باز شدن نسخهٔ جدید را خودش پیدا می‌کند و پیش از نصب از شما می‌پرسد.

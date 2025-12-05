# 📊 Financial Dashboard — ศูนย์ดูแลและฟื้นฟูสุขภาพผู้สูงอายุแบบครบวงจร

> Dashboard แสดงผลข้อมูลทางการเงินสำหรับโครงการศูนย์ดูแลและฟื้นฟูสุขภาพผู้สูงอายุแบบครบวงจร พร้อมกราฟและตารางวิเคราะห์ทางการเงิน 5 ปี

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
[![HTML5](https://img.shields.io/badge/HTML5-E34F26?logo=html5&logoColor=white)](https://developer.mozilla.org/en-US/docs/Web/HTML)
[![TailwindCSS](https://img.shields.io/badge/Tailwind_CSS-38B2AC?logo=tailwind-css&logoColor=white)](https://tailwindcss.com/)
[![Chart.js](https://img.shields.io/badge/Chart.js-FF6384?logo=chart.js&logoColor=white)](https://www.chartjs.org/)


## ✨ Features

### 📈 Multi-page Dashboard
- **Overview** - ภาพรวมผลประกอบการและงบลงทุน
- **P&L (Profit & Loss)** - งบกำไรขาดทุน 5 ปี พร้อมตารางสรุป
- **Investment** - โครงสร้างงบลงทุนรายหมวด
- **Scenario** - วิเคราะห์จุดคุ้มทุน (Simple Payback)

### 📊 Interactive Charts
- 📉 Revenue vs Net Profit (Line Chart)
- 📊 P&L Multiline (4 metrics)
- 📊 Gross vs Net Profit (Bar Chart)
- 🍩 Investment Breakdown (Doughnut Chart)
- 📊 Investment by Category (Horizontal Bar)
- 📈 Payback Analysis Graph

### 🎨 Design Highlights
- 🌙 Dark theme with modern UI
- 📱 Responsive design (Mobile & Desktop)
- ⚡ Fast loading - Pure Static HTML
- 🎯 No backend required
- 🚀 Works offline

## 🛠 Technologies

| Technology | Purpose |
|-----------|---------|
| HTML5 | Structure |
| TailwindCSS | Styling (via CDN) |
| Chart.js | Data Visualization |
| Vanilla JavaScript | Interactivity |

## 📦 Installation & Usage

### Option 1: Local Usage (Quick Start)
```bash
# Clone the repository
git clone https://github.com/kittiphongkubkub/financial_dashboard_noscroll-main.git

# Navigate to directory
cd financial_dashboard_noscroll-main

# Open in browser
# Simply double-click index.html
# or use a local server:
python -m http.server 8000
# Then visit http://localhost:8000
```

### Option 2: GitHub Pages Deployment
1. Fork or clone this repository
2. Go to **Settings** → **Pages**
3. Select **main** branch as source
4. Click **Save**
5. Your dashboard will be live at `https://github.com/kittiphongkubkub/financial_dashboard_noscroll/`

### Option 3: Direct File Usage
- Download `index.html`
- Open with any modern browser (Chrome, Firefox, Edge, Safari)
- Works completely offline! ✅

## 📁 Project Structure

```
financial_dashboard_noscroll-main/
├── index.html          # Main dashboard file (เนื้อหาทั้งหมด)
├── README.md           # Documentation
├── LICENSE             # MIT License
└── .gitignore          # Git ignore rules
```

## 📸 Screenshots

_Add screenshots here after deployment_

### Overview Page
![Overview Dashboard](#)

### P&L Analysis
![P&L Dashboard](#)

### Investment Breakdown
![Investment Dashboard](#)

## 💾 Data Source

Dashboard นี้ใช้ข้อมูลจาก:
- `ตาราง P&L.xlsx` - งบกำไรขาดทุน 5 ปี
- `งบประมาณการลงทุน.xlsx` - งบประมาณลงทุนรายหมวด

ข้อมูลถูก hard-coded ใน JavaScript ภายใน `index.html` สามารถแก้ไขได้โดยตรง

## 🔧 Customization

### แก้ไขข้อมูล
เปิดไฟล์ `index.html` และแก้ไขตัวแปรใน `<script>` section:

```javascript
const years = ["Year 1", "Year 2", "Year 3", "Year 4", "Year 5"];
const revenue = [20.16, 31.68, 43.2, 48.96, 51.84];
const netProfit = [-17.19, -7.76, 1.74, 7.3, 9.36];
// ... etc
```

### แก้ไขสี/ธีม
แก้ไข CSS ใน `<style>` section หรือ Tailwind classes ใน HTML

## 🤝 Contributing

Contributions, issues, and feature requests are welcome!

1. Fork the project
2. Create your feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

## 📄 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## 👤 Author
 https://github.com/kittiphongkubkub


## 🙏 Acknowledgments

- [TailwindCSS](https://tailwindcss.com/) for beautiful styling
- [Chart.js](https://www.chartjs.org/) for interactive charts
- Data based on elderly care center financial projections

---

⭐ **If you find this project useful, please consider giving it a star!** ⭐

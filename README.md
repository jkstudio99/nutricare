# 🫀 NutriCare DASH

ระบบติดตามสุขภาพผู้ป่วยความดันโลหิตสูงแบบครบวงจร

## 📋 ภาพรวม

NutriCare DASH เป็นระบบสุขภาพออนไลน์ที่พัฒนาขึ้นเพื่อช่วยผู้ป่วยความดันโลหิตสูงในการติดตามสุขภาพ ควบคุมอาหาร และจัดการข้อมูลทางการแพทย์ผ่านแพลตฟอร์มเว็บแอปพลิเคชัน

## ✨ คุณสมบัติหลัก

### 🏥 สำหรับผู้ป่วย

- 📊 **Dashboard** - ภาพรวมสุขภาพแบบ real-time
- 💉 **ความดันโลหิต** - บันทึกและแสดงกราฟแนวโน้ม
- 🥗 **บันทึกอาหาร** - ติดตามการรับประทานอาหาร DASH
- 💧 **ปริมาณน้ำ** - บันทึกการดื่มน้ำวันละ
- 🏃 **กิจกรรม** - บันทึกการออกกำลังกาย
- ⚖️ **น้ำหนัก** - ติดตามน้ำหนักและเป้าหมาย
- 💊 **การรับประทานยา** - เตือนและบันทึกการทานยา
- 🍽️ **คำแนะนำอาหาร** - สูตรอาหารเหมาะสำหรับผู้ป่วยความดัน

### 👨‍⚕️ สำหรับแพทย์/ผู้ดูแล

- 👥 **จัดการผู้ป่วย** - ดูข้อมูลผู้ป่วยทั้งหมด
- 📈 **รายงานสุขภาพ** - วิเคราะห์ข้อมูลแบบละเอียด
- 💬 **การสื่อสาร** - แชทและให้คำแนะนำ

### 🌐 คุณสมบัติทั่วไป

- 🌓 **Dark Mode** - รองรับโหมดมืด/สว่าง
- 🌏 **หลายภาษา** - ไทย/English
- 📱 **Responsive Design** - รองรับทุกขนาดหน้าจอ
- 🔐 **Authentication** - ระบบ login ปลอดภัย
- 📊 **Interactive Charts** - กราฟสวยงามด้วย ApexCharts

## 🛠️ Tech Stack

### Frontend

- **React 18** + **Vite** - Modern React framework
- **TailwindCSS v4** - Utility-first CSS framework
- **Zustand** - State management
- **ApexCharts** - Interactive charts
- **Lucide Icons** - Beautiful icons
- **TanStack Query** - Server state management
- **Axios** - HTTP client

### Backend

- **OpenGenetics PHP v1.0.0** - PHP framework
- **MySQL** - Database
- **JWT** - Authentication
- **RBAC** - Role-based access control

## 🚀 การติดตั้ง

### Prerequisites

- Node.js 18+
- PHP 8+
- MySQL 8+
- Composer
- npm/yarn

### Backend Setup

```bash
cd backend
composer install
cp .env.example .env
# Configure database in .env
php bin/genetics serve
```

### Frontend Setup

```bash
cd frontend
npm install
cp .env.example .env
# Configure API URL in .env
npm run dev
```

## 📱 การใช้งาน

### Test Accounts

| Role    | Email                   | Password      |
| ------- | ----------------------- | ------------- |
| Admin   | `admin@opengenetics.io` | `password`    |
| Patient | `patient1@nutricare.io` | `password123` |
| Doctor  | `doctor1@nutricare.io`  | `password123` |

### Access URLs

- **Frontend:** http://localhost:5173
- **Backend API:** http://127.0.0.1:8080
- **Database:** MySQL on 127.0.0.1:3308

## 📁 โครงสร้างโปรเจค

```
nutricare/
├── backend/                 # OpenGenetics PHP backend
│   ├── app/                # Application code
│   ├── config/             # Configuration files
│   ├── database/           # Database migrations
│   └── public/             # Public assets
├── frontend/               # React frontend
│   ├── src/
│   │   ├── components/     # React components
│   │   ├── pages/          # Page components
│   │   ├── stores/         # Zustand stores
│   │   ├── lib/            # Utilities
│   │   └── i18n/           # Internationalization
│   ├── public/             # Static assets
│   └── dist/               # Build output
└── README.md
```

## 🎨 Design System

- **Colors:** Teal/Mint primary palette
- **Typography:** Noto Sans Thai (9-level scale)
- **Spacing:** Apple HIG guidelines
- **Components:** Custom UI library with dark mode

## 📊 API Endpoints

ระบบมี **28 API endpoints** ครอบคลุม:

- Authentication (Login, Register, Logout)
- Patient Management
- Health Records (BP, Weight, Activities)
- Diet & Nutrition
- Medications
- Reports

## 🔐 Security

- JWT-based authentication
- Role-based access control (RBAC)
- Input validation & sanitization
- CORS protection
- SQL injection prevention

## 🌍 Internationalization

รองรับ 2 ภาษา:

- 🇹🇭 Thai (default)
- 🇺🇸 English

## 📱 Responsive Breakpoints

- **Mobile:** 375px+ (Bottom navigation)
- **Tablet:** 768px+ (Desktop sidebar)
- **Desktop:** 1440px+ (Full layout)

## 🤝 Contributing

1. Fork the repository
2. Create feature branch (`git checkout -b feature/amazing-feature`)
3. Commit changes (`git commit -m 'Add amazing feature'`)
4. Push to branch (`git push origin feature/amazing-feature`)
5. Open Pull Request

## 📄 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## 👥 Team

- **Frontend Developer:** React/Vite/TailwindCSS Specialist
- **Backend Developer:** PHP/MySQL Expert
- **UI/UX Designer:** Healthcare Experience Designer

## 📞 Support

สำหรับข้อสงสัยหรือปัญหาการใช้งาน:

- 📧 Email: support@nutricare.io
- 📱 Line: @nutricare
- 🌐 Website: https://nutricare.io

---

**🫀 NutriCare DASH - ดูแลสุขภาพหัวใจคุณอย่างมีความสุข**

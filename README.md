<p align="center" style="display: flex; justify-content: center; align-items: center; flex-wrap: wrap; gap: 15px;">
  <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/react/react-original.svg" height="55" title="React" />
  <img src="https://blogger.googleusercontent.com/img/b/R29vZ2xl/AVvXsEiSqT1SJ2-10Nt4SfENScW41TuQBkqvHpApsNeBw6h44_KLbyCywu8NO_y_d4ug6bfLFPKM-z0groqAkCdzBy9oS1GTxpOI_IU0YEANjFETgemUnLKqTZnxAgqQtEJ3aWHEVfyxMmAK4fA/s1600/spring-boot-logo.png" height="55" title="Spring Boot" />
  <img src="https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcTP5BaOYcOW7WwQHHIzIjxfyH1giTa3_KSrJQ&s" height="55" style="border-radius:10px;" title="Cloudinary" />
  <img src="https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcSJ5ME3FQKPOVK6xNfgIdxPNfVYyqGQi5G73Q&s" height="55" style="border-radius:10px;" title="Postgres" />
</p>





# DomiCare - Professional Cleaning & Maintenance Platform


> **A modern, transparent, and secure platform connecting customers with professional cleaning and maintenance services.**

> Developed by **Domicare-Team** for the
>
> <h4 align="center">
>   <a href="#" target="_blank">
>      Project-Based Learning 3 (PBL3) – DUT
>   </a>
> </h4>

---

## Quick Start

```bash
# Clone the repository
git clone https://github.com/hnagnurtme/DomiCare.git

cd DomiCare
# Configure environment variables
cp .env.example .env
# Edit .env with your API keys and credentials

# Start all services with Docker Compose
docker compose up -d

# View logs
docker compose logs -f


```
**What's included:**
- Frontend (React + Vite) → http://localhost:3000
- Backend (Spring Boot) → http://localhost:8080

---

## Key Features

| **Role** | **Functions** | **Test Account** |
|-----------|----------------|------------------|
| **Customer** | - Browse and search for services<br>- Book and manage appointments<br>- Request consultations<br>- Track booking history<br>- Rate and review| 📧 `testuser@gmail.com`<br>🔑 `Testuser@123` |
| **Sales Staff** | - Manage bookings and consultations<br>- Generate revenue reports<br>- Receive real-time notifications<br>- Update personal information | 📧 `testsale@gmail.com`<br>🔑 `Testsale@123` |
| **Administrator** | - Manage users and staff<br>- Create and manage services<br>- Handle discounts and promotions<br>- Monitor system performance | 📧 `testadmin@gmail.com`<br>🔑 `Testadmin@123` |

---

## Screenshots

### Home Page
<p align="center">
  <img src="docs/image/image-login.png" alt="Login Page" width="800"/>
  <br/>
  <em>User authentication and login interface</em>
</p>

<p align="center">
  <img src="docs/image/image-homepage.png" alt="Home Page" width="800"/>
  <br/>
  <em>Main landing page with service overview</em>
</p>

<p align="center">
  <img src="docs/image/image-gioithieu.png" alt="Intro / About" width="800"/>
  <br/>
  <em>About section introducing DomiCare services</em>
</p>

### Products Page
<p align="center">
  <img src="docs/image/image-search.png" alt="All Products" width="800"/>
  <br/>
  <em>Service search and filtering functionality</em>
</p>

<p align="center">
  <img src="docs/image/image-fullproduct.png" alt="Products Grid" width="800"/>
  <br/>
  <em>Complete product catalog view</em>
</p>

### Admin / Dashboard
<p align="center">
  <img src="docs/image/image-dashboard.png" alt="Admin Dashboard" width="800"/>
  <br/>
  <em>Administrative dashboard with analytics and metrics</em>
</p>

<p align="center">
  <img src="docs/image/image-donhang.png" alt="Admin Orders" width="800"/>
  <br/>
  <em>Order management interface for administrators</em>
</p>

<p align="center">
  <img src="docs/image/image-admin-dichvu.png" alt="Admin Services" width="800"/>
  <br/>
  <em>Service management and configuration panel</em>
</p>

### Admin - Staff & Management
<p align="center">
  <img src="docs/image/image-admin-nhanvien.png" alt="Admin Staff" width="800"/>
  <br/>
  <em>Staff management and personnel overview</em>
</p>

<p align="center">
  <img src="docs/image/image-admin-update.png" alt="Admin Update Form" width="800"/>
  <br/>
  <em>User and staff information update interface</em>
</p>

### User / Mobile Views
<p align="center">
  <img src="docs/image/image-user-lichsu-tatca.png" alt="Bookings History (User)" width="800"/>
  <br/>
  <em>User booking history and transaction records</em>
</p>

<p align="center">
  <img src="docs/image/image-matkhau.png" alt="Mobile - Reset Password / Email" width="800"/>
  <br/>
  <em>Password recovery and email verification flow</em>
</p>

<p align="center">
  <img src="docs/image/image-thongbao.png" alt="Notifications / Toasts" width="800"/>
  <br/>
  <em>Real-time notification system</em>
</p>

### Sales / Notifications
<p align="center">
  <img src="docs/image/image-sale-donhang.png" alt="Sales - Orders" width="800"/>
  <br/>
  <em>Sales staff order management interface</em>
</p>

<p align="center">
  <img src="docs/image/image-tuvan.png" alt="Consultation / Requests" width="800"/>
  <br/>
  <em>Customer consultation and service request handling</em>
</p>

## Technology Stack

### Backend
- Spring Boot
- Spring Security with JWT Authentication
- Hibernate & JPA
- RESTful API Design

### Frontend
- React 18 + TypeScript
- Vite 5
- TailwindCSS 3

### Database & Storage
- PostgreSQL
- Cloudinary for media storage

## Team

Built with ❤️ by **DomiCare Team**:

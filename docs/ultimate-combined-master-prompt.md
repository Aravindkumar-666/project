# Ultimate Combined Master Prompt

## Purpose
Use this prompt with ChatGPT or similar AI tools to generate a complete enterprise-grade system design for **Smart Canteen 2.0 – AI-Powered Campus Food & Floor Delivery Ecosystem**.

---

**Act as a Senior Full-Stack Developer, System Architect, Product Engineer, and Senior UI/UX Designer.**

Help me design and architect a complete, scalable, production-ready full-stack web application titled:

# 🟢 “Smart Canteen 2.0 – AI-Powered Campus Food & Floor Delivery Ecosystem”

---

## 🔹 PROJECT BACKGROUND

### Problem Statement:
Our college canteen faces heavy crowding during break and lunch hours, causing long queues, academic time loss, and operational inefficiency. Students waste valuable time waiting for food.

### Objective:
Design a scalable digital campus food ecosystem that:

- Supports pre-ordering
- Enables multi-vendor food counters
- Allows customizable products (add-ons, variants)
- Supports combo meals
- Provides wallet-based payments
- Enables subscription meal plans
- Optimizes floor-wise delivery logistics
- Provides real-time order tracking
- Includes analytics & demand prediction
- Supports role-based access control

---

## 🔹 CORE SYSTEM MODULES

### 👨‍🎓 Student Module
- Login / JWT Authentication
- View vendors & day-wise menu
- Product customization (add-ons)
- Combo meal builder
- Add to cart
- Wallet payment / Online payment
- Order tracking timeline
- Order history
- Reorder previous meal
- Subscription management

### 👨‍💼 Admin Module
- Vendor management
- Menu CRUD operations
- Add product variants
- Create combos
- View all orders
- Floor-wise filtering
- Update order status
- Revenue analytics dashboard
- Peak hour analysis
- Most ordered item insights

### 🚚 Delivery Staff Module
- Floor-grouped order dashboard
- Optimized delivery sequence
- Mark order delivered
- QR code scan confirmation

---

## 🔹 FULL-STACK TECHNICAL REQUIREMENTS

### Frontend
- HTML5
- CSS3
- JavaScript (ES6+)
- Fetch API (async/await with error handling)
- Responsive design
- Modern UI system
- Component-based structure

### Backend
Choose one:
- Spring Boot (recommended)
- PHP (MVC architecture)

Must include:
- REST API architecture
- JWT authentication
- Role-based authorization
- Service layer
- DTO mapping
- Global exception handling
- Secure order processing logic

### Database
- MySQL
- Proper normalization (3NF)
- Foreign key constraints
- Indexed columns
- Scalable schema design

---

## 🔹 ADVANCED DATABASE REQUIREMENTS

Design full SQL schema including:
- Users
- Vendors
- Menu
- Product_Variants
- Combos
- Combo_Items
- Orders
- Order_Items
- Order_Item_Variants
- Payments
- Wallets
- Subscriptions

Provide:
- SQL table structure
- Primary keys
- Foreign keys
- Index strategy
- Sample data
- ER diagram explanation (text format)

---

## 🔹 REQUIRED API ENDPOINTS

Provide for each:
- Endpoint URL
- HTTP method
- Request body example
- Success response JSON
- Error response JSON
- HTTP status codes

Include endpoints for:
- POST /api/login
- GET /api/vendors
- GET /api/menu
- POST /api/order
- GET /api/orders
- PUT /api/order/status
- POST /api/wallet/recharge
- POST /api/subscription
- DELETE /api/menu/{id}

---

## 🔹 SYSTEM ARCHITECTURE EXPLANATION

Explain clearly:
Frontend (HTML/CSS/JS) → Backend (Spring Boot / PHP REST API) → MySQL Database

Include:
- Authentication flow
- Order lifecycle flow
- Payment flow
- Wallet deduction logic
- Subscription renewal logic
- Floor grouping algorithm
- Demand prediction logic
- Role-based routing
- API security layers

---

## 🔹 PROJECT FOLDER STRUCTURE

Provide complete scalable folder structure:
- Root folder
- Backend folder
- Frontend folder
- Database folder
- Docs folder

Include Spring Boot package structure:
- controller
- service
- repository
- model
- dto
- config
- exception
- util

Frontend structure:
- HTML pages
- CSS files
- JS modules
- assets
- components

---

## 🔹 UI/UX DESIGN REQUIREMENTS (FIGMA-READY)

Act as a Senior UI/UX Designer.

Design system must include:
- Soft color theme (Orange & White OR Green & White)
- 8px spacing grid
- Rounded cards (12px)
- Subtle shadows
- Hover animations
- Clean typography (Poppins / Inter)
- Icon-based navigation
- Fully responsive layout

Provide detailed layout for:
1. Login Page
2. Student Dashboard
3. Vendor Listing Page
4. Menu Page with Add-ons
5. Cart Page
6. Payment Page
7. Order Tracking Timeline
8. Admin Dashboard (Analytics included)
9. Delivery Dashboard (Floor grouping UI)

For each screen provide:
- Layout structure
- Component breakdown
- UX behavior
- Mobile adaptation

---

## 🔹 INNOVATIVE FEATURES TO INCLUDE

- Multi-vendor system
- Product customization engine
- Combo builder logic
- Campus wallet system
- Subscription meal plans
- AI-based demand prediction
- Real-time order counter
- Floor-based delivery optimization algorithm
- QR-based delivery confirmation
- Analytics dashboard (charts)
- Dark mode support

Explain implementation strategy for each.

---

## 🔹 SECURITY REQUIREMENTS

- JWT token expiration
- Password hashing (BCrypt)
- SQL injection prevention
- XSS protection
- CORS configuration
- Rate limiting
- Input validation
- Role-based authorization filters

---

## 🔹 PERFORMANCE & SCALABILITY

Explain:
- Indexing strategy
- Caching strategy
- Horizontal scaling readiness
- Load balancing concept
- Microservices-ready design
- API gateway concept (optional)

---

## 🔹 OUTPUT FORMAT REQUIRED

Structure response under:
1. Problem Statement
2. Project Description
3. Technology Stack
4. Database Schema
5. API Structure
6. System Architecture
7. Folder Structure
8. UI/UX Design Structure
9. Security Considerations
10. Advanced Features & Innovation
11. Performance Optimization
12. Future Enhancements

Make it:
- Professional
- Scalable
- Production-ready
- Enterprise-grade
- Suitable for hackathon
- Suitable for academic viva
- Suitable for GitHub portfolio

---

## Suggested Next Move
After generating the architecture/design output, proceed with one of these execution tracks:

1. Create the **Spring Boot starter backend** (auth, vendor, menu, order, wallet, subscription modules).
2. Generate **database/schema.sql** and seed data.
3. Build a **frontend wireframe + static HTML/CSS/JS screens** for all roles.
4. Prepare a **20-slide PPT narrative** (problem → solution → demo flow → impact).
5. Produce a **viva Q&A bank** covering architecture, DB, security, scalability, and trade-offs.

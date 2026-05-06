# Jua kali connect

## over view

Jua kali coonect is full- stack digital platform designed to empower artisans, small-scale fabricants and inform ssector businesses (jua kali) by providing tools for managing operations ,connecting wuth customers and streamlining  processes.

The system bridges the gap between tradition craftsmanship and mordern technology by offering features such as job tracking, customer management, inventory control and digital payments.

## Features

### User management
- User registration and authentication
- Role-based access (Admin, Artisan, Customer)
- Profile management

Inventory Management
- Track raw materials and finished goods
- Low stock alerts
- Category-based organization

Order & Job Tracking
- Create and manage customer orders
- Track job progress (Pending → In Progress → Completed)
- Assign jobs to artisans

Payments Integration
- M-Pesa integration for seamless payments
- Payment status tracking
- Transaction history

Communication
- Real-time chat between customers and artisans
- Notifications for updates and messages

Dashboard & Analytics
- Admin dashboard with system overview
- Business insights (sales, orders, revenue)
- Activity logs

## Tech stack

**frontend**
- React.jd
- Tailwindcss
- Axios
- ReduxQL

**Dev0ps & Development**
- Docker
- Github Actions (CI/CD)
- Cloudhosting (AWS/ RENDER / AZURE )

**Project structure**
text
jua-kali-connect/
│
├── frontend/                # React application
│   ├── src/
│   ├── components/
│   └── pages/
│
├── backend/                # Django application
│   ├── apps/
│   ├── models/
│   ├── views/
│   └── api/
│
├── docker/                 # Docker configurations
├── docs/                   # Documentation
├── .env.example            # Environment variables template
├── requirements.txt
├── package.json
└── README.md

## Installation & Setup
**Bash**

cd ../frontend

# Install dependencies
npm install

# Start development server
npm start

![ website ](asset/image/download)

## API Endpoints


|**Methods**  |**Endpoints**  | **Description** |
| ------------- | ------------- |-------- |
|
 Post    |`api\auth\register\`  | Register user |    
  Post   |`api\auth\login\`  | login user |   
   Get   |`api\orders\`  | list orders|    
   post   |`api\orders\`  | create order |  
   Get |`api\inventory\`  | view inventory |   

## Environment Variables

Create a .env file in both frontend and backend directories:

Backend

**Plaintext**

SECRET_KEY=your_secret_key
DEBUG=True
DB_NAME=jua_kali_db
DB_USER=postgres
DB_PASSWORD=your_password
MPESA_CONSUMER_KEY=your_key
MPESA_CONSUMER_SECRET=your_secret


Frontend

**Plaintext**

REACT_APP_API_URL=http://localhost:8000/api


Testing

**Bash**

# Backend tests
python manage.py test

# Frontend tests
npm test


Deployment

1. **Build frontend:** npm run build
2. **Use Docker for full-stack deployment:** docker-compose up --build
3. **Deploy on:**
   * AWS (EC2 / S3)
   * Azure
   * Render / Vercel (frontend)

Contributing

Contributions are welcome!

1. Fork the repository
2. Create a new branch (`feature/your-feature`)
3. Commit your changes
4. Push to your branch
5. Open a Pull Request

License

This project is licensed under the MIT License.

## Author

**Juanita kavata**

* GitHub: [https://github.com/juan-ita]
* Email: your-email: kavatajuanita@example.com

## Vision

To digitize and empower the Jua Kali sector by providing accessible, scalable, and efficient software solutions that enhance productivity and market reach.

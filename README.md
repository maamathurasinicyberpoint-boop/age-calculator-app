# Manoj Babu CSC - Complete Service Management System

A comprehensive web application for ordering CSC (Common Service Centre) services with complete order management, payment processing, and document upload capabilities.

## 🌟 Features

### Core Functionality
- **Service Catalog Management**: Admin-controlled service list with pricing
- **Order Management**: Complete order lifecycle from placement to completion
- **Payment Integration**: QR code-based payment system
- **Document Upload**: Support for Aadhaar and other document uploads
- **Real-time Status Tracking**: Live order status updates
- **Role-based Access**: Separate user and admin interfaces

### User Features
- **Browse Services**: View available services with pricing
- **Place Orders**: Select services, enter details, upload documents
- **Payment**: Scan QR code for easy payment
- **Order History**: Track all orders and their status
- **Document Upload**: Upload Aadhaar or other required documents

### Admin Features
- **Service Management**: Add, edit, delete services and pricing
- **Order Management**: View all orders, update status
- **Customer Management**: View customer details and order history
- **Real-time Dashboard**: Monitor all business activities

## 🔐 Simple Login System

This application uses a simple, name-based login flow with two roles. No passwords or authentication are used—this is designed for demo/navigation purposes.

- **login.html**: Enter a name and choose User Login or Admin Login
  - User Login → user-dashboard.html
  - Admin Login → admin-dashboard.html
- **user-dashboard.html**: User interface for ordering services and tracking orders
- **admin-dashboard.html**: Admin interface for managing services and orders

**Note**: Since this is a static site demo, these pages do not implement real authentication or access control. Anyone can visit any page directly.

## 📱 Navigation Structure

- **Home page**: index.html (includes links to all sections)
- **Login page**: login.html
- **User Dashboard**: user-dashboard.html
- **Admin Dashboard**: admin-dashboard.html

## 🛍️ How to Use (Customer Flow)

1. **Login**: Go to login.html and enter your name, select "User Login"
2. **Browse Services**: View available services with current pricing
3. **Select Service**: Click on any service card to select it
4. **Fill Details**: Enter your phone number and complete address
5. **Upload Documents**: Optionally upload Aadhaar or other required documents
6. **Payment**: Scan the QR code and pay the amount
7. **Confirm**: Click "I Have Paid" to complete the order
8. **Track**: View your order status in "My Orders" section

## ⚙️ Admin Management

### Service Management
- Add new services with custom pricing
- Edit existing service names and prices
- Delete services no longer offered
- All changes are saved automatically

### Order Management
- View all customer orders in real-time
- Update order status (Pending → Processing → Completed)
- Track customer information and contact details
- Monitor payment status and delivery progress

### Status Options
- **Pending**: Order placed, awaiting processing
- **Processing**: Order being prepared/processed
- **Completed**: Service delivered successfully
- **Cancelled**: Order cancelled

## 🏪 Services Offered

Manoj Babu CSC provides convenient home delivery for various government and citizen services including:

### Government Services
- PAN Card application/correction
- Aadhaar card updates and corrections
- Birth/Death certificates
- Income/Caste certificates
- Voter ID applications

### Utility Services
- Electricity bill payments
- Water bill payments
- Gas bill payments
- Mobile/DTH recharges

### Digital Services
- Digital documentation
- Form filling assistance
- Online application support
- Document printing/scanning

## 💳 Payment System

- **QR Code Integration**: Easy scan-and-pay functionality
- **UPI Support**: Integrated with UPI ID: manojbabu@paytm
- **Real-time Processing**: Immediate order confirmation
- **Secure**: No sensitive payment data stored locally

## 📄 Document Upload

- **File Support**: Accepts .jpg, .jpeg, .png, .pdf formats
- **Aadhaar Integration**: Special support for Aadhaar card uploads
- **Optional Upload**: Documents can be uploaded during order placement
- **Secure Storage**: Files are handled securely for privacy

## 🔧 Technical Details

### Technology Stack
- **Frontend**: HTML5, CSS3, JavaScript (ES6+)
- **Storage**: Browser localStorage for demo data persistence
- **Styling**: Custom CSS with responsive design
- **Architecture**: Client-side only (static site)

### Data Storage
- **Services**: Stored in localStorage as JSON
- **Orders**: Persistent order data with customer details
- **Session**: User name passed via URL parameters
- **Files**: File references stored (actual files handled by browser)

### Browser Compatibility
- Modern browsers with localStorage support
- Mobile-responsive design
- Touch-friendly interface

## 🚀 Deployment

This application is automatically deployed via GitHub Pages and is accessible at:
[Your GitHub Pages URL]

### Local Development
1. Clone the repository
2. Open index.html in a web browser
3. No build process required - pure HTML/CSS/JS

## 📊 Demo Data

The application comes pre-loaded with sample services:
- PAN Card Application (₹150)
- PAN Card Correction (₹120)
- Aadhaar Card Update (₹80)
- Birth Certificate (₹100)
- And more...

Admins can modify this list through the admin dashboard.

## 🎯 Use Cases

### For Customers
- Order government services from home
- Track service delivery status
- Upload required documents easily
- Make secure payments via UPI

### For Service Providers
- Manage service catalog and pricing
- Track all customer orders
- Update delivery status
- Monitor business performance

## 📞 Contact & Support

For service inquiries and support:
- **CSC Provider**: Manoj Babu
- **Payment UPI**: manojbabu@paytm
- **Service Area**: Local community

## 🔮 Future Enhancements

- Real authentication system
- SMS/Email notifications
- Payment gateway integration
- Advanced reporting dashboard
- Mobile app development
- Multi-language support

---

**About CSC Services**: Common Service Centres (CSC) are access points for delivery of various electronic services to villages and remote areas. Manoj Babu CSC brings these services to your doorstep for your convenience.

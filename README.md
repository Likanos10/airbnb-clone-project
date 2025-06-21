# airbnb-clone-project
## **Project Overview**  
A full-stack clone of AirBnB, allowing users to browse property listings, view details, and make bookings.  

## **Project Goals**  
- Build a responsive, user-friendly booking platform.  
- Implement frontend (React) and backend (Node.js/Express) functionality.  
- Use a database (PostgreSQL/MongoDB) to store listings and user data.  
- Follow best practices in coding, testing, and deployment.  

## **Tech Stack**  
- **Frontend:** React, HTML, CSS, JavaScript  
- **Backend:** Node.js, Express  
- **Database:** PostgreSQL / MongoDB  
- **Version Control:** Git & GitHub  
- **Design:** Figma (for UI/UX mockups)  

## **Getting Started**  
1. Clone this repo:  
   ```bash
   git clone https://github.com/your-username/airbnb-clone-project.git

## UI/UX Design Planning

### Design Goals
- Create an intuitive, responsive interface for seamless property browsing and booking
- Ensure fast loading times and smooth navigation
- Maintain visual consistency with clean typography, spacing, and color schemes
- Follow accessibility best practices (WCAG compliance)

### Key Features
- Property search & filtering
- High-quality images in listings
- Interactive maps (location preview)
- User reviews & ratings
- Secure & simple checkout flow

### Page Descriptions

| Page | Description |
|------|------------|
| Property Listing View | Displays available properties as cards with images, price, location, and ratings. Includes search/filter options. |
| Listing Detailed View | Shows full property details (photos, amenities, host info, reviews, booking calendar). |
| Simple Checkout View | A minimal, step-by-step booking form (dates, guest count, payment, confirmation). |

### Why User-Friendly Design Matters
- Reduces bounce rates - A confusing layout drives users away
- Improves conversions - Smooth checkout = more completed bookings
- Enhances trust - Professional design increases credibility
- Mobile-first approach - Over 50% of bookings happen on phones


### **Figma Design Specifications**

#### **Color Styles**
- Primary: `#FF5A5F` (Airbnb-style coral)
- Secondary: `#008489` (Teal)
- Background: `#FFFFFF` (White)
- Text: `#222222` (Dark Gray)
- Accent: `#FFB400` (Yellow)
- Error: `#FF0000` (Red)

#### **Typography**
| Type          | Font Family | Weight | Size  | Use Case               |
|---------------|------------|--------|-------|------------------------|
| Heading 1     | Circular   | Bold   | 32px  | Page titles            |
| Heading 2     | Circular   | SemiBold | 24px  | Section headers        |
| Body Text     | Circular   | Regular | 16px  | Paragraphs             |
| Button Text   | Circular   | Medium | 14px  | CTA buttons            |
| Caption       | Circular   | Light  | 12px  | Image captions         |

#### **Why Design Properties Matter**
1. **Consistency** - Ensures uniform visuals across all screens
2. **Efficiency** - Developers can implement styles faster
3. **Brand Identity** - Maintains recognizable look-and-feel
4. **Responsiveness** - Guides adaptive design for all devices
5. **Team Alignment** - Serves as single source of truth for designers/devs


## **Project Roles and Responsibilities**

| Role                | Key Responsibilities | Contribution to Project |
|---------------------|----------------------|-------------------------|
| **Project Manager** | - Define project timeline<br>- Coordinate team efforts<br>- Risk management | Ensures on-time delivery and team alignment |
| **Frontend Devs**   | - Implement UI components<br>- Ensure responsive design<br>- Integrate with APIs | Builds user-facing interfaces |
| **Backend Devs**    | - Develop APIs<br>- Database design<br>- Authentication logic | Powers application functionality |
| **Designers**       | - Create Figma mockups<br>- Define design system<br>- UX research | Shapes visual identity and usability |
| **QA/Testers**      | - Write test cases<br>- Report bugs<br>- Performance testing | Ensures product reliability |
| **DevOps Engineer** | - CI/CD pipeline setup<br>- Deployment automation<br>- Monitoring | Maintains deployment infrastructure |
| **Product Owner**   | - Define requirements<br>- Prioritize features<br>- Stakeholder communication | Bridges business and technical needs |
| **Scrum Master**    | - Facilitate standups<br>- Remove blockers<br>- Maintain agile process | Optimizes team workflow |


## **UI Component Patterns**

### **Planned Components**

#### 1. Navbar
- **Purpose**: Main navigation and user authentication
- **Features**:
  - Logo and brand identity
  - Search bar
  - User profile dropdown
  - Responsive hamburger menu (mobile)

#### 2. Property Card
- **Purpose**: Display property listings
- **Features**:
  - Property image carousel
  - Price, location, and rating
  - Favorite/heart icon
  - Responsive grid layout

#### 3. Search Filters
- **Purpose**: Refine property searches
- **Features**:
  - Date picker
  - Guest counter
  - Price range slider
  - Amenities checklist

#### 4. Footer
- **Purpose**: Site navigation and information
- **Features**:
  - Quick links
  - Social media icons
  - Copyright information
  - Contact details

#### 5. Booking Modal
- **Purpose**: Handle reservation flow
- **Features**:
  - Date selection
  - Price calculation
  - Payment form
  - Confirmation message

### **Component Architecture**
- **Reusable**: Designed for multiple use cases
- **Modular**: Independent functionality
- **Responsive**: Mobile-first approach
- **Accessible**: WCAG compliant

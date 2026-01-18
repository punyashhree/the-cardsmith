# The CardSmith - Greeting Card Generator & Store

## Project Overview

**The CardSmith** is a web-based application that allows users to create, customize, and purchase personalized greeting cards online. This single-page application provides an intuitive interface for designing cards for various occasions like birthdays, graduations, and anniversaries.

## Project Objectives

1. **Simplify Card Creation**: Enable users to generate personalized greeting cards with minimal effort
2. **Customization**: Allow users to customize messages, recipient names, and card types
3. **E-commerce Integration**: Provide a complete purchase flow with pricing calculation and order confirmation
4. **User Feedback Management**: Support uploading and displaying customer feedback
5. **Data Persistence**: Enable saving and loading of card messages for future use

## Key Features

### 1. User Authentication
- Secure login system with username and password validation
- Session management with logout functionality
- Clean and professional login interface

### 2. Card Customization
- **Multiple Card Types**: Birthday, Graduation, and Anniversary cards
- **Auto-Generate Messages**: Message generation based on card type
- **Custom Messages**: Users can write their own personalized messages
- **Recipient & Sender Names**: Personalize cards with names (letters-only validation)
- **Live Preview**: Real-time card preview with dynamic color themes

### 3. Pricing & Purchase System
- **Fixed Pricing**: Rs 50 per card (constant pricing model)
- **Quantity Selection**: Order 1-100 cards at once
- **Dynamic Pricing Calculation**:
  - Subtotal calculation (Price × Quantity)
  - Tiered shipping costs:
    - 1-2 cards: Rs 50
    - 3-5 cards: Rs 100
    - 6+ cards: Rs 150
  - Real-time total calculation

### 4. Order Management
- **Order Confirmation Modal**: Professional order summary popup
- **Unique Order Numbers**: 6-digit random order number generation
- **Receipt Download**: Text-based receipt with complete order details
- **Order Details Display**: Card type, recipient, quantity, and pricing breakdown

### 5. Data Management
- **Save Messages**: Download card messages as .txt files
- **Load Messages**: Upload previously saved messages
- **Feedback System**: Upload customer feedback files (Name: Message format)
- **Feedback Display**: Grid-based feedback card layout with avatars

### 6. Validation & Error Handling
- **Name Validation**: Only alphabetic characters and spaces allowed
- **Real-time Error Display**: Instant feedback with red borders and error messages
- **Purchase Validation**: Ensures valid names before completing purchase
- **Empty Field Checks**: Prevents submission with incomplete data

## Technologies Used

### Frontend
- **HTML5**: Semantic markup and structure
- **CSS3**: 
  - Flexbox and Grid layouts for responsive design
  - CSS animations (floating card, button hover effects)
  - Linear gradients for modern aesthetic
  - Media queries for mobile responsiveness
- **JavaScript (Vanilla ES5)**: 
  - DOM manipulation
  - Event handling
  - Form validation with Regular Expressions
  - File upload and download functionality
  - Dynamic pricing calculations

## Project Structure

```
the-cardsmith/
│
├── index.html          # Single-page application (HTML, CSS, JS combined)
└── README.md          # Project documentation
```

## How to Run

1. **Download the Project**
   - Download `index.html` file

2. **Open in Browser**
   - Double-click `index.html` to open in default browser
   - OR right-click → Open with → Choose browser (Chrome, Firefox, Edge, etc.)

3. **Login**
   - Enter any username and password
   - Click "Login" button

4. **Start Creating Cards**
   - Select card type from dropdown
   - Enter recipient and sender names
   - Click "Generate" for auto message or type custom message
   - Click "Preview" to see card design
   - Adjust quantity if needed
   - Click "Purchase Card" to complete order

## Usage Guide

### Creating a Card

1. **Login** with any credentials
2. **Select Card Type**: Choose from Birthday, Graduation, or Anniversary
3. **Enter Names**: 
   - Recipient Name (who receives the card)
   - Your Name (sender)
   - Note: Only letters and spaces allowed
4. **Create Message**:
   - Click "Generate" for auto-generated message
   - OR type your custom message
5. **Preview**: Click "Preview" to see card design with your message
6. **Save** (optional): Save your message as a text file
7. **Load** (optional): Load a previously saved message

### Making a Purchase

1. **Check Pricing**: 
   - Card price is fixed at Rs 50
   - Adjust quantity (1-100 cards)
   - View automatic price calculation
2. **Purchase**: Click "Purchase Card" button
3. **View Confirmation**: Order confirmation modal appears
4. **Download Receipt**: Click "Download Receipt" for order details
5. **Close**: Click "Close" to return to main screen

### Managing Feedback

1. **Prepare File**: Create a .txt file with feedback in format:
   ```
   John Doe: Great service and beautiful cards!
   Jane Smith: Fast delivery, loved the quality
   Anonymous: Amazing customization options
   ```
2. **Upload**: Click "Load Feedback Data" button
3. **View**: Feedback appears in card grid below
4. **Close**: Click "Close" button to hide feedback section

## Business Model

### Revenue Streams
1. **Card Sales**: Rs 50 per card (fixed pricing)
2. **Bulk Orders**: Volume-based shipping encourages larger orders
3. **Future Premium Features**: Custom designs, expedited shipping

### Cost Structure
- **Card Printing**: Per-unit printing cost
- **Shipping**: Tiered based on order size
- **Platform Maintenance**: Web hosting and domain

### Target Market
- Individuals celebrating personal occasions
- Businesses sending cards to employees/clients
- Event planners needing bulk cards
- Students and young professionals

## Developer Information

**Project Name**: The CardSmith  
**Name**: Punyashree G
**Type**: Web Application (Single Page Application)  
**Development Stack**: HTML, CSS, JavaScript

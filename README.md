# InvioLite - Professional Invoice Generator

A modern, professional invoice generator built with vanilla JavaScript. Perfect for creating beautiful invoices, quotes, and proforma invoices for your business.

## ✨ Features

### Core Features
- **Live Preview** - See your invoice update in real-time as you type
- **Multiple Document Types** - Create invoices, proforma invoices, and quotes
- **Multi-Currency Support** - Support for TRY, USD, EUR, GBP
- **Configurable Tax Rate** - Set your own tax/VAT percentage
- **Discount Support** - Apply percentage or fixed amount discounts
- **Unlimited Line Items** - Add as many products/services as needed
- **Professional Design** - Clean, modern invoice template

### Advanced Features
- **PDF Export** - Generate high-quality PDF files
- **Data Persistence** - Auto-save to browser storage
- **Export/Import** - Backup and restore your invoices
- **Print Ready** - Optimized print styles
- **Responsive Design** - Works on desktop and mobile devices
- **Secure** - XSS protection and input validation

## 🚀 Quick Start

1. **Download or clone** this repository
2. **Open** `index.html` in a modern web browser
3. **Start creating** your invoices!

No installation or build process required - it's ready to use immediately.

## 📋 Usage

### Creating an Invoice

1. **Fill in document details:**
   - Select document type (Invoice, Proforma Invoice, or Quote)
   - Choose currency
   - Enter invoice number
   - Set issue and expiry dates

2. **Add customer information:**
   - Company/Name
   - Address
   - Phone number

3. **Add line items:**
   - Click "+ Kalem Ekle" to add items
   - Enter description, quantity, and unit price
   - Remove items with the "Sil" button

4. **Configure pricing:**
   - Set tax rate (default: 20%)
   - Add discount (percentage or fixed amount)

5. **Add notes** (optional):
   - Payment terms
   - Delivery details
   - Other important information

6. **Export:**
   - Click "PDF İndir" to generate PDF
   - Click "Yazdır" to print
   - Click "Kaydet" to save to browser storage
   - Click "Dışa Aktar" to download JSON backup

## 🎨 Customization

### Company Information

Edit the company details in `index.php`:
- Company name (line 128)
- Address (line 129-130)
- Email (line 131)
- Phone (line 132)
- Website (line 193)

### Logo

Place your logo file as `logo.png` in the project root. The logo will automatically appear in the header and footer. If no logo is found, the space will be hidden gracefully.

### Styling

Customize colors and styles in `style.css`:
- Dark theme colors (lines 1-21)
- Invoice paper colors (lines 12-20)
- Fonts and typography

## 💾 Data Management

### Auto-Save
The application automatically saves your work to browser localStorage every 2 seconds after changes.

### Manual Save
Click "Kaydet" to manually save your current invoice.

### Export
Click "Dışa Aktar" to download a JSON backup file containing:
- All line items
- Form data
- Settings (tax rate, discount)
- Timestamp

### Import
Click "İçe Aktar" to restore from a previously exported JSON file.

## 🔒 Security Features

- **XSS Protection** - All user inputs are sanitized
- **Input Validation** - Prevents invalid data entry
- **Safe DOM Manipulation** - Uses textContent instead of innerHTML where possible

## 📱 Browser Support

- Chrome (latest)
- Firefox (latest)
- Safari (latest)
- Edge (latest)

## 🛠️ Technical Details

### Technologies Used
- Vanilla JavaScript (ES6+)
- HTML5
- CSS3
- html2pdf.js (for PDF generation)

### File Structure
```
invoice-generator/
├── index.php          # Main HTML file
├── script.js          # Application logic
├── style.css          # Styles and themes
├── logo.png           # Company logo (optional)
└── README.md          # This file
```

## 📄 License

This is a commercial product. All rights reserved.

**Commercial License Agreement**

This software is licensed, not sold. By purchasing and using InvioLite, you agree to the terms of the Commercial License Agreement included in the `LICENSE.md` file.

**Key Points:**
- ✅ Use in your projects (personal or commercial)
- ✅ Modify to suit your needs
- ✅ Use in end products you sell
- ❌ Redistribute or resell the source code
- ❌ Share with others who haven't purchased a license
- ❌ Remove copyright notices

For full license terms, please refer to `LICENSE.md`.

## 🆘 Support

For support, feature requests, or bug reports, please contact:
- Email: info@imgera.com
- Website: imgera.com

## 🎯 Roadmap

Future enhancements may include:
- Multiple invoice templates
- Email sending functionality
- Invoice numbering automation
- Customer database
- Multi-language support
- Cloud storage integration

## 📝 Changelog

### Version 2.0 (Current)
- ✅ Complete code refactoring
- ✅ Security improvements (XSS protection)
- ✅ PDF generation with html2pdf.js
- ✅ Data persistence (localStorage)
- ✅ Export/Import functionality
- ✅ Configurable tax rate
- ✅ Discount support
- ✅ Better error handling
- ✅ User notifications
- ✅ Responsive design improvements

### Version 1.0
- Initial release
- Basic invoice generation
- Print functionality

---

**Made with ❤️ by Lemos Web**

# 📄 Invoice Generator

A modern, responsive, and feature-rich invoice generator web application that allows you to create professional invoices instantly. Generate, preview, and download invoices as PDF or images with ease!

![Invoice Generator](https://img.shields.io/badge/version-2.0.0-blue.svg)
![License](https://img.shields.io/badge/license-MIT-green.svg)
![HTML5](https://img.shields.io/badge/HTML5-E34F26?logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?logo=css3&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?logo=javascript&logoColor=black)

## 🚀 Quick Start

**Live Demo:** [https://durgesh-v-shukla.github.io/invoice-generator/](https://durgesh-v-shukla.github.io/invoice-generator/)

**Local Use:**
1. Download `index.html`
2. Open in any modern browser
3. Start creating invoices!

No installation, no sign-up, completely free!

## ✨ Features

### � **Simple & Clean Interface**
- **Minimalist Design** - Only essential options visible initially
- **Smart Toggles** - Show/hide sections as needed
- **Additional Information Toggle** - Master toggle to reveal all advanced options
- **Default Simplicity** - Only date field enabled by default

### �🎨 **Multiple Professional Templates**
- **Modern Template** - Sleek gradient design with contemporary styling
- **Classic Template** - Traditional bordered layout for formal invoices
- **Minimal Template** - Clean and simple with accent colors
- **Simple Template** - Table-focused black and white design

### 📋 **Flexible Invoice Customization**
- **Always Visible:**
  - Template selection
  - Invoice date (enabled by default)
  - Products/Services section
  - Totals and calculations
  
- **Additional Information (Optional):**
  - Company Name
  - Invoice Number (with auto-generate)
  - Bill From (Company Details)
  - Bill To (Client Details)
  - Due Date (with day name)
  - Signature

### 🛒 **Dynamic Product Management**
- Add unlimited products/services
- Automatic subtotal calculation per product
- Real-time total calculations
- Easy product removal
- Fields: Product Name, Quantity, Rate, Total

### 💰 **Advanced Calculations**
- Automatic subtotal calculation
- Optional discount feature (percentage-based)
- Grand total calculation
- Multi-currency support (₹, $, €, £, ¥)
- Real-time preview updates

### 📱 **Responsive Design**
- Fully mobile-friendly
- Tablet and desktop optimized
- Adaptive layouts for all screen sizes
- Touch-friendly interface

### 💾 **Export Options**
- **PDF Download** - Generate professional PDF invoices
- **Image Download** - Save as high-quality images
- **Print Ready** - Optimized for printing
- **Real-time Preview** - See changes instantly

### ✅ **Smart Validation**
- Required field validation
- Error messages and feedback
- Toast notifications for user actions
- Input validation for numbers and dates

## 🚀 How to Use

### 1. **Open the Application**
Simply open the application in any modern web browser or visit:
**https://durgesh-v-shukla.github.io/invoice-generator/**

### 2. **Select Template**
Choose from 4 professional templates in the Template Style dropdown.

### 3. **Add Products/Services**
- Click "➕ Add Product" to add items
- Enter product name, quantity, and rate
- Total is calculated automatically
- Remove items with the 🗑️ button

### 4. **Set Invoice Date (Default)**
- The date field is enabled by default
- Select your invoice date
- Day name is automatically displayed

### 5. **Enable Additional Information (Optional)**
- Toggle "Show Additional Information" to reveal advanced options:
  - Company Name
  - Invoice Number (with auto-generate button)
  - Bill From (your company details)
  - Bill To (client details)
  - Due Date
  - Signature
- Check/uncheck individual options as needed

### 6. **Apply Discount (Optional)**
- Check "Apply Discount" if needed
- Enter discount percentage (e.g., 10 for 10%)
- Discount is applied to subtotal automatically

### 7. **Preview & Download**
- Preview updates in real-time as you type
- Click "📥 PDF" to download as PDF
- Click "🖼️ Image" to download as image

## 🎯 Use Cases

### **Perfect For:**
- 💼 Freelancers and consultants
- 🏢 Small businesses
- 🛍️ Online sellers
- 👨‍💼 Service providers
- 📊 Quick billing needs
- 🎓 Students learning web development

### **Common Scenarios:**
- Generate client invoices
- Create quotations
- Bill for services rendered
- E-commerce order invoices
- Consulting fee invoices
- Freelance project billing

## 💡 Key Benefits

### ⚡ **Fast & Easy**
- No installation required
- No sign-up or login needed
- Works offline (after initial load)
- Instant generation
- Clean, uncluttered interface

### 🎨 **Professional**
- Clean, modern designs
- Customizable templates
- Professional formatting
- Brand-ready output
- Progressive disclosure (show only what you need)

### 💯 **Free & Open Source**
- Completely free to use
- No hidden costs
- Open source code
- Customize as needed
- Self-hosted option available

### 🔒 **Privacy First**
- All data stays in your browser
- No server uploads
- No data collection
- Complete privacy

## 🛠️ Technical Details

### **Built With:**
- **HTML5** - Structure and semantics
- **CSS3** - Styling and responsive design
- **Vanilla JavaScript** - Logic and interactions
- **html2canvas** - HTML to canvas conversion
- **jsPDF** - PDF generation
- **Google Fonts** - Poppins typography

### **Browser Compatibility:**
- ✅ Chrome (recommended)
- ✅ Firefox
- ✅ Safari
- ✅ Edge
- ✅ Opera

### **Features:**
- No dependencies beyond included CDN libraries
- Lightweight (single HTML file)
- Fast loading and rendering
- Responsive grid layout
- CSS animations and transitions

## 📁 File Structure

```
Invoice Generator/
├── index.html       # Main application file (all-in-one)
├── .gitignore       # Git ignore file
└── README.md        # Documentation (this file)
```

## 🎓 How It Helps

### **For Users:**
1. **Save Time** - Generate invoices in seconds, not hours
2. **Save Money** - Free alternative to expensive invoicing software
3. **Stay Organized** - Professional invoices improve business image
4. **Work Anywhere** - Browser-based, works on any device
5. **Maintain Privacy** - Your data never leaves your computer
6. **Start Simple** - Minimal interface, add complexity only when needed
7. **No Learning Curve** - Intuitive design, start creating immediately

### **For Developers:**
1. **Learn Modern Web Development** - Clean, well-structured code
2. **Understand DOM Manipulation** - Real-world JavaScript examples
3. **Explore CSS Grid & Flexbox** - Responsive layout techniques
4. **Study PDF Generation** - Browser-based document creation
5. **Practice Form Validation** - User input handling

## 🔧 Customization

### **Enable All Fields by Default:**
Edit the "Additional Information" checkbox in the HTML:
```html
<input type="checkbox" id="show-additional-info" checked>
```

### **Change Default Currency:**
Edit the currency dropdown in the HTML:
```html
<select id="currency">
  <option value="₹">₹ INR</option>
  <!-- Add your currency here -->
</select>
```

### **Modify Templates:**
Edit the CSS classes for each template:
- `.template-modern` - Modern template styles
- `.template-classic` - Classic template styles
- `.template-minimal` - Minimal template styles
- `.template-simple` - Simple template styles

### **Add New Fields:**
Follow the existing pattern:
1. Add checkbox toggle
2. Add form group with input
3. Add to preview section
4. Update JavaScript validation

## 🐛 Known Limitations

- Large invoices (100+ products) may slow down preview
- PDF generation quality depends on browser
- Some fonts may not embed in PDF
- Offline use requires prior page load

## 📝 License

This project is open source and available under the [MIT License](LICENSE).

## 🤝 Contributing

Contributions, issues, and feature requests are welcome! Feel free to:
- Report bugs
- Suggest new features
- Submit pull requests
- Improve documentation

## 📞 Support

If you encounter any issues or have questions:
1. Check the documentation above
2. Review the code comments
3. Open an issue on GitHub
4. Contact the developer

## 🌟 Acknowledgments

- **html2canvas** by Niklas von Hertzen
- **jsPDF** by James Hall
- **Google Fonts** for Poppins typeface
- Inspired by the need for simple, free invoicing tools

## 🎉 Version History

### v2.0.0 (Current - November 2025)
- ✅ **Simplified UI** - "Additional Information" master toggle
- ✅ **Cleaner Interface** - Only date field visible by default
- ✅ **Progressive Disclosure** - Show advanced options on demand
- ✅ **Improved UX** - Less overwhelming for new users
- ✅ **GitHub Pages Deployment** - Live demo available

### v1.0.0 (Initial Release)
- ✅ 4 professional templates
- ✅ Fully responsive design
- ✅ Optional fields system
- ✅ Discount feature
- ✅ PDF and Image export
- ✅ Real-time validation
- ✅ Multi-currency support
- ✅ Day names on dates
- ✅ Auto-collapsing sections

---

**Made with ❤️ for freelancers and small businesses**

*Star ⭐ this repository if you found it helpful!*

# TechEdge Survey Form

A clean, professional survey form built with vanilla HTML, CSS, and JavaScript. This project demonstrates form design best practices with a modern, user-friendly interface.

## 🌟 Features

### Form Design
- **Clean Layout**: Professional, centered design with card-based container
- **Organized Sections**: Form fields grouped into logical sections
- **Responsive Design**: Works seamlessly on desktop, tablet, and mobile devices
- **Visual Feedback**: Focus states and hover effects for better user experience
- **Logo Integration**: TechEdge branding with logo display

### Form Sections
- **Personal Information**: Name, email, phone number
- **Demographics**: Age, gender, location
- **Survey Questions**: Multiple choice and text input fields
- **Submission**: Clear submit button with confirmation page

### User Experience
- **Intuitive Navigation**: Clear section headers and organized layout
- **Form Validation**: HTML5 form validation
- **Success Confirmation**: Dedicated success page after submission
- **Accessibility**: Semantic HTML structure for screen readers

## 🚀 Getting Started

### Prerequisites
- A modern web browser (Chrome, Firefox, Safari, or Edge)
- No server or build process required

### Installation

1. **Clone or download the project**
   ```bash
   git clone <repository-url>
   cd "Techedge Survey"
   ```

2. **Open the survey form**
   - Simply open `index.html` in your web browser
   - Or serve the directory using a local web server

### Using a Local Server (Optional)

**Python 3:**
```bash
python -m http.server 8000
```

**Node.js (using http-server):**
```bash
npx http-server
```

Then navigate to `http://localhost:8000/index.html`

## 📁 Project Structure

```
Techedge Survey/
├── index.html              # Main survey form
├── message.html            # Success confirmation page
├── techedge.png           # TechEdge logo
└── README.md              # This documentation file
```

## 🛠️ Technologies & Frameworks

### Core Technologies
- **HTML5**: Semantic markup and form elements
- **CSS3**: Custom styling with modern CSS features
- **Vanilla JavaScript (ES6+)**: Form handling and interactivity

### Design Approach
- **No Framework Dependencies**: Built entirely with vanilla web technologies
- **Custom CSS**: All styling is custom-written for optimal performance
- **Lightweight**: Minimal dependencies for fast loading times
- **Responsive**: Mobile-first design approach

## 🎨 Design Features

### Color Scheme
- **Primary Blue**: `#007bff` - Accent color for borders and focus states
- **Background**: `#f5f5f5` - Light gray background
- **Card Background**: `#ffffff` - White card container
- **Section Background**: `#f9f9f9` - Light gray for form sections
- **Text Colors**: Dark gray (`#333`) for headings, medium gray (`#555`, `#666`) for labels and descriptions

### Typography
- **Font Family**: Arial, sans-serif
- **Font Sizes**: Responsive sizing for different screen sizes
- **Font Weights**: Bold for labels, normal for input text

### Layout
- **Max Width**: 800px centered container
- **Padding**: Consistent spacing throughout
- **Border Radius**: 10px for main container, 8px for sections, 5px for inputs
- **Shadows**: Subtle box shadows for depth

## 📝 Form Fields

### Personal Information
- Full Name (text input)
- Email Address (email input with validation)
- Phone Number (tel input)

### Demographics
- Age (number input)
- Gender (select dropdown)
- Location (text input)

### Survey Questions
- Multiple choice questions
- Text area for open-ended responses
- Checkbox options
- Radio button selections

## 🔧 Customization

### Updating Branding
1. Replace `techedge.png` with your logo
2. Update the logo path in `index.html`
3. Adjust logo size in CSS if needed

### Modifying Form Fields
1. Add or remove form sections in `index.html`
2. Update the corresponding CSS for styling
3. Adjust JavaScript if custom validation is needed

### Changing Colors
The color scheme is defined throughout the CSS:
- Search for `#007bff` to change primary accent color
- Search for `#f5f5f5` to change background color
- Search for `#f9f9f9` to change section background

### Adding Form Validation
Currently uses HTML5 validation. To add custom JavaScript validation:
1. Add event listeners to form fields
2. Implement validation logic
3. Display error messages as needed

## 📱 Responsive Design

The form is fully responsive and optimized for:
- **Desktop**: 800px max-width centered layout
- **Tablet**: Adapts to smaller screens with adjusted padding
- **Mobile**: Full-width on small screens with touch-friendly inputs

## 🔄 Form Submission

### Current Implementation
- Form submits to `message.html` (success page)
- No backend integration (static form)

### Future Enhancements
- Backend API integration for data storage
- Email notification on submission
- Database storage for survey responses
- Analytics and reporting dashboard

## 🎯 Best Practices

### Accessibility
- Semantic HTML structure
- Proper label associations
- Keyboard navigation support
- Screen reader friendly

### Performance
- Minimal external dependencies
- Optimized CSS
- Fast loading times
- Lightweight design

### User Experience
- Clear form labels
- Helpful placeholder text
- Visual feedback on interactions
- Success confirmation page

## 🐛 Troubleshooting

### Form Not Displaying Correctly
- Check browser compatibility (modern browsers required)
- Verify all CSS is loading properly
- Check browser console for errors

### Logo Not Showing
- Ensure `techedge.png` is in the same directory
- Check file path in HTML
- Verify image file format (PNG, JPG supported)

### Form Submission Issues
- Verify `message.html` exists in the same directory
- Check form action attribute
- Ensure all required fields are filled

## 📄 License

This project is available for use under your preferred license.

## 🤝 Contributing

1. Fork the repository
2. Create a feature branch (`git checkout -b feature/new-feature`)
3. Commit your changes (`git commit -m 'Add new feature'`)
4. Push to the branch (`git push origin feature/new-feature`)
5. Open a Pull Request

## 📧 Contact

For questions or support, please contact the development team.

---

**Built with ❤️ for efficient data collection**

*Last updated: Based on project analysis*


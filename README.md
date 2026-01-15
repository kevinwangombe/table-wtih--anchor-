
## 🎨 Features

### 1. **HTML Structure (`index.html`)**
- Clean semantic HTML5 markup
- Responsive table layout with proper `<thead>` and `<tbody>` sections
- Five example websites with:
  - Clickable names (opens in new tab via `target="_blank"`)
  - Category classification
  - Brief description
- Proper document structure with meta tags for viewport responsiveness

### 2. **CSS Styling (`style.css`)**
- **Overall Styling**:
  - Light cyan background (`lightcyan`)
  - Centered page title
  - Table centered with 80% width and automatic margins

- **Table Design**:
  - Collapsed borders for clean look
  - Alternating row colors (`#f2f2f2` for even rows)
  - Header with green background (`#4CAF50`) and white text
  - Adequate padding (12px) for readability
  - Arial font family for clean typography

- **Link Styling**:
  - Bold blue links (`#0066cc`)
  - Hover effect: orange color (`#ff6600`) with underline
  - No default underline (appears only on hover)

## 🛠️ Technologies Used
- **HTML5**: For content structure and semantics
- **CSS3**: For styling and visual presentation
- **Responsive Design**: Works on both desktop and mobile devices

## 📱 Responsive Design
The table is designed to be responsive:
- Uses 80% width to adapt to different screen sizes
- Maintains readability on mobile devices
- Consistent padding and spacing across devices

## 🎯 Usage Instructions

1. **Basic Use**:
   - Simply open `index.html` in a web browser
   - Click on any website name to visit it (opens in new tab)
   - Browse the directory by category or description

2. **Customization**:
   - To add new websites, copy the table row structure in `index.html`:
     ```html
     <tr>
       <td><a href="URL" target="_blank">Website Name</a></td>
       <td>Category</td>
       <td>Description</td>
     </tr>
     ```
   - Modify colors in `style.css` to match your brand
   - Adjust table width by changing the `width` property in the table CSS rule

## 🎨 Color Scheme
- **Background**: `lightcyan`
- **Table Header**: `#4CAF50` (green) with white text
- **Even Rows**: `#f2f2f2` (light gray)
- **Links**: `#0066cc` (blue) → `#ff6600` (orange) on hover
- **Borders**: `#ddd` (light gray)

## 📝 Code Highlights

### HTML Best Practices
- Proper use of table semantics (`thead`, `tbody`)
- External CSS linking (`/assets/style.css`)
- Accessibility-friendly structure
- All external links open in new tabs (non-intrusive)

### CSS Best Practices
- Efficient selectors
- Hover states for interactive elements
- Consistent spacing and alignment
- Clean, maintainable code structure

## 🔧 Potential Enhancements
1. **JavaScript Functionality**:
   - Add search/filter capabilities
   - Implement sorting by columns
   - Add favorite/bookmark feature

2. **Advanced Styling**:
   - Add animations/transitions
   - Implement dark mode
   - Add responsive breakpoints for mobile optimization

3. **Features**:
   - Category filtering buttons
   - Copy URL functionality
   - Rating system for websites

## 🤝 Contributing
Feel free to fork this project and submit pull requests with improvements. Some areas for contribution include:
- Additional website entries
- Enhanced mobile responsiveness
- New styling themes
- Accessibility improvements

## 📄 License
This project is open source and available for educational and personal use.

## 👤 Author
Created as a demonstration project for HTML/CSS table styling with interactive elements.

---

**Happy Browsing!** 🌐

# Fanlab Website

A modern static website project for Fanlab (Future Advanced Network Lab) at Southeast University. This project is built using pure HTML, CSS, and JavaScript without any backend requirements.

## 📁 Project Structure

```
Mainpage/
├── index.html                 # Home page
├── pages/                     # Sub-pages directory
│   ├── about.html            # About Fanlab
│   ├── research.html         # Research Projects
│   ├── team.html             # Team Members
│   ├── publications.html     # Publications
│   ├── contact.html          # Contact Us
│   └── news.html             # News & Updates
├── css/                       # Stylesheet files
│   ├── style.css             # Main stylesheet
│   └── responsive.css        # Responsive design
├── js/                        # JavaScript files
│   └── main.js               # Main interaction script
├── images/                    # Image assets directory
└── .github/
    └── copilot-instructions.md  # Project documentation
```

## ✨ Key Features

- ✅ **Responsive Design** - Fully compatible with desktop, tablet, and mobile devices
- ✅ **Modern UI Design** - Clean color scheme and beautiful layout
- ✅ **Navigation System** - Sticky navigation bar with mobile menu toggle
- ✅ **Animation Effects** - Scroll animations and smooth transitions
- ✅ **Multi-page Structure** - 7 complete pages showcasing lab information
- ✅ **Contact Form** - Functional contact form for inquiries
- ✅ **Framework-Free** - Pure HTML, CSS, JavaScript for fast loading

## 📄 Page Descriptions

### Home (index.html)
- Hero information section
- Research directions showcase
- Latest news highlights
- Lab statistics

### About Us (pages/about.html)
- Lab introduction
- Core mission and history
- Research facilities
- Core values
- Major achievements timeline

### Research (pages/research.html)
- Current project listings
- Project details (PI, status)
- Research focus areas
- Project categorization

### Team (pages/team.html)
- Lab director information
- Senior researchers
- Postdoctoral fellows
- PhD student information
- Visiting scholars

### Publications (pages/publications.html)
- Publication statistics
- Latest papers list
- Paper details and abstracts
- Publication categorization

### Contact (pages/contact.html)
- Contact information (address, phone, email)
- Online message form
- Department contact details
- FAQ section

### News (pages/news.html)
- News articles list
- Detailed article content
- Category tags
- Pagination

## 🎨 Design Features

### Color Scheme
- **Primary Color** (#2c3e50) - Deep blue-gray for headings
- **Secondary Color** (#3498db) - Sky blue for links and interactive elements
- **Accent Color** (#e74c3c) - Red for special highlights

### Typography
- Clear text hierarchy
- Comfortable line spacing (1.6)
- Readable font combinations

### Responsive Breakpoints
- Desktop: 1200px+
- Tablet: 768px - 1024px
- Mobile: 480px - 768px
- Small mobile: < 480px

## 🚀 How to Use

### View the Website
1. **Method 1: Direct file opening**
   ```bash
   # Open index.html in your browser
   ```

2. **Method 2: Local server (recommended)**
   ```bash
   # Python 3
   python -m http.server 8000
   
   # Python 2
   python -m SimpleHTTPServer 8000
   ```
   Then visit `http://localhost:8000`

3. **Method 3: Other servers**
   ```bash
   # Node.js (http-server)
   npx http-server

   # Ruby
   ruby -run -ehttpd . -p8000
   ```

## 📝 Customization

### Update Basic Information
1. **Lab Name and Tagline** - Edit titles and descriptions in HTML files
2. **Contact Details** - Update phone, email, and address in `pages/contact.html`
3. **Team Members** - Add or remove member cards in `pages/team.html`
4. **Research Projects** - Update project information in `pages/research.html`
5. **Publications** - Modify paper listings in `pages/publications.html`

### Style Customization
- **Change Colors** - Edit CSS variables in `css/style.css` (`:root` section)
- **Adjust Fonts** - Modify `font-family` in `css/style.css`
- **Modify Spacing** - Adjust `padding` and `margin` values in CSS

### Add Images
1. Place image files in the `images/` folder
2. Reference in HTML: `<img src="../images/filename.jpg">`

## 🔧 Technology Stack

- **HTML5** - Semantic markup structure
- **CSS3** - Grid layout, Flexbox, transitions and animations
- **JavaScript** - Mobile menu toggle, scroll animations, form handling
- **Browser Compatibility** - All modern browsers supported

## 💻 File Sizes

- HTML files combined: ~80KB
- CSS files: ~15KB
- JavaScript: ~3KB
- **Very small overall footprint with fast loading**

## 📱 Browser Support

- ✅ Chrome/Edge (latest versions)
- ✅ Firefox (latest versions)
- ✅ Safari (latest versions)
- ✅ Mobile browsers (iOS Safari, Chrome Android)

## 🎯 Improvement Suggestions

To further enhance the website, consider:

1. **Add Images and Media**
   - Lab facility photos
   - Team member avatars
   - Research results visualization

2. **Implement Search Functionality**
   - Paper search
   - News search
   - Member search

3. **Multi-Language Support**
   - Chinese version
   - Other languages

4. **Backend Management System**
   - Dynamic news addition
   - Team member management
   - Form data storage

5. **SEO Optimization**
   - Enhanced metadata
   - Structured data markup
   - Sitemap generation

6. **Analytics Integration**
   - Google Analytics
   - Visitor tracking
   - Data analysis

## 📧 Feedback & Support

For questions or suggestions, please contact:
- Email: contact@fanlab.seu.edu.cn
- Visit our Contact page
- Call our main laboratory line

## 📄 License

This project is open source and can be freely used and modified.

---

**Created Date**: March 27, 2026
**Last Updated**: March 27, 2026
**Organization**: Fanlab, Southeast University


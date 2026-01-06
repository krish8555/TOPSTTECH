# Ourcba DTC - Disability Tax Credit Application

A responsive web application converted from Figma design to HTML and CSS, featuring a modern, clean interface for disability tax credit applications.

## 🎨 Design

This project is a pixel-perfect implementation of the Figma design provided for Ourcba DTC (Disability Tax Credit) application system.

## 📁 Project Structure

```
/
├── index.html                        # Landing page with navigation
├── all-pages.html                    # Complete page directory (37 pages)
├── style.css                         # Landing page styles
├── all-pages.css                     # All pages navigation styles
├── common.css                        # Shared styles for all pages
├── login.html / login.css           # Authentication page
├── welcome.html / welcome.css       # Refund application form
├── admin.html / admin.css           # Admin dashboard
├── agent.html / agent.css           # Agent management
├── disability.html                  # Disability information
├── disability-details.html          # Detailed disability assessment
├── family-members.html              # Family member management
├── add-relative.html                # Add family relative
├── questions.html                   # Assessment questionnaire
├── reassessment.html                # Reassessment management
├── add-reassessment.html            # Create new reassessment
├── django-admin.html                # Django administration
├── chat.html                        # Real-time messaging
├── calls.html                       # Call management
├── current-calls.html               # Active calls monitoring
├── calls-admin.html                 # Call administration
├── agent-calls.html                 # Agent call records
├── call-schedule.html               # Call scheduling
├── document-t2201.html              # T2201 tax form
├── document-schedule5.html          # Schedule 5 document
├── document-mail-stickers.html      # Mail sticker management
├── document-complaints.html         # Service complaints
├── analytics.html                   # Analytics dashboard
├── analytics-calls.html             # Call statistics
├── analytics-collections.html       # Collections analytics
├── analytics-refunds.html           # Refunds analytics
├── report-page.html                 # Generated reports
├── report-2.html                    # Detailed report analysis
├── opportunity-card.html            # Opportunity management
├── opportunity-mail.html            # Opportunity communications
├── opportunity-ddi.html             # DDI information popup
├── agent-tasks.html                 # Task management
├── meeting-schedule.html            # Meeting scheduler
├── popup.html                       # General popup
├── complaint-popup.html             # Complaint form popup
├── group-237.html                   # Group interface 237
├── group-238.html                   # Group interface 238
├── images/                          # 37 extracted design assets
├── README.md                        # Project documentation
└── .gitignore                       # Git ignore configuration
```

## ✨ Features

### Pages (All 37 Frames Implemented)
1. **Landing Page** - Central navigation hub
2. **All Pages Directory** - Complete page index with categorization
3. **Authentication** - Login with email/password and Google sign-in
4. **Application Forms** - Welcome, Disability, Family Members, Questions, Reassessments
5. **Admin Dashboards** - Admin, Agent, Django Administration
6. **Communication** - Chat, Calls, Call Scheduling, Agent Calls
7. **Documents** - T2201, Schedule 5, Mail Stickers, Service Complaints
8. **Analytics** - Dashboard, Call Statistics, Collections, Refunds
9. **Reports** - Report pages with detailed analysis
10. **Opportunities** - Opportunity cards, email, DDI popups
11. **Tasks & Meetings** - Agent tasks, Meeting scheduler
12. **Modals & Popups** - General and complaint popups
13. **Groups** - Group management interfaces

### Design Features
- ✅ Fully responsive design (mobile, tablet, desktop)
- ✅ Smooth animations and transitions
- ✅ Interactive hover effects
- ✅ Modern gradient backgrounds
- ✅ Clean form layouts with validation
- ✅ Fixed live chat button on all pages
- ✅ Accessible focus states
- ✅ Pure HTML/CSS (no JavaScript required)

## 🚀 Getting Started

### Viewing the Website

1. Clone the repository:
```bash
git clone https://github.com/krish8555/TOPSTTECH.git
cd TOPSTTECH
```

2. Open in a browser:
   - Simply open `index.html` in your web browser
   - Or use a local development server:
   ```bash
   # Python 3
   python -m http.server 8000
   
   # Python 2
   python -m SimpleHTTPServer 8000
   
   # Node.js (with http-server)
   npx http-server
   ```

3. Navigate to `http://localhost:8000` in your browser

## 📱 Responsive Breakpoints

- **Mobile**: < 480px
- **Tablet**: 481px - 768px
- **Desktop**: > 768px

All pages are optimized for each breakpoint with appropriate layout adjustments.

## 🎨 Color Scheme

The project uses CSS variables for consistent theming:

```css
--primary-color: #1E88E5;     /* Primary blue */
--primary-hover: #1976D2;      /* Darker blue for hover states */
--secondary-color: #E3F2FD;    /* Light blue background */
--text-dark: #212121;          /* Dark text */
--text-light: #757575;         /* Light text */
--border-color: #E0E0E0;       /* Border gray */
--white: #FFFFFF;              /* White */
```

## 🖼️ Screenshots

### Desktop Views
- **Landing Page**: Modern card-based navigation
- **Login Page**: Clean authentication form
- **Welcome Form**: Comprehensive multi-step form
- **Admin Dashboard**: Professional admin interface

### Mobile Views
- Optimized layouts for small screens
- Touch-friendly button sizes
- Readable font sizes
- Simplified navigation

## 🛠️ Technologies Used

- **HTML5**: Semantic markup
- **CSS3**: Modern styling with:
  - CSS Grid & Flexbox
  - CSS Variables (Custom Properties)
  - Keyframe Animations
  - Media Queries
  - Pseudo-elements
- **Font Awesome**: Icon library (via CDN)

## 🎯 Browser Compatibility

- Chrome (latest)
- Firefox (latest)
- Safari (latest)
- Edge (latest)
- Mobile browsers (iOS Safari, Chrome Mobile)

## 📄 License

This project is part of the TOPSTTECH repository.

## 👥 Contributors

- Converted from Figma design to HTML/CSS
- Implemented responsive layouts
- Added animations and interactions

## 🤝 Contributing

If you'd like to contribute to this project:

1. Fork the repository
2. Create a feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

## 📞 Support

For questions or support, please use the live chat feature available on all pages or create an issue in the repository.

---

**Note**: This is a frontend-only implementation. Backend functionality for form submissions, authentication, and data management would need to be implemented separately.

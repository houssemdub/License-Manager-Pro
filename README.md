# 📋 License Manager Pro for WordPress

**Enterprise-grade license management system with stunning UI, real-time analytics, and intelligent expiry tracking.**

![Version](https://img.shields.io/badge/version-2.0.0-blue.svg)
![WordPress](https://img.shields.io/badge/WordPress-5.0%2B-brightgreen.svg)
![PHP](https://img.shields.io/badge/PHP-7.4%2B-purple.svg)
![License: GPL v3](https://img.shields.io/badge/License-GPL%20v3-red.svg)
![PRs Welcome](https://img.shields.io/badge/PRs-welcome-brightgreen.svg)

> **A professional WordPress plugin for comprehensive software license management with modern UI, advanced analytics dashboard, automated expiry notifications, and complete audit trails.**

Perfect for IT departments, software companies, agencies, and businesses managing multiple software licenses across their organization.

---

## 📋 Table of Contents

- [Features](#-features)
- [Screenshots](#-screenshots)
- [Installation](#-installation)
- [Quick Start](#-quick-start)
- [Usage Guide](#-usage-guide)
- [Email Notifications](#-email-notifications)
- [Import & Export](#-import--export)
- [Analytics & Reporting](#-analytics--reporting)
- [Customization](#-customization)
- [API & Hooks](#-api--hooks)
- [Requirements](#-requirements)
- [File Structure](#-file-structure)
- [FAQs](#-faqs)
- [Troubleshooting](#-troubleshooting)
- [Roadmap](#-roadmap)
- [Contributing](#-contributing)
- [Credits](#-credits)
- [License](#-license)

---

## 🌟 Features

### 📦 **Comprehensive License Management**

✅ **Unlimited Licenses** - Store and manage unlimited software licenses  
✅ **Complete Metadata** - Track product, manufacturer, brand, version, type  
✅ **License Types** - Perpetual, Subscription, Trial, OEM, Volume, Educational  
✅ **Seat Management** - Track and allocate user seats  
✅ **User Assignment** - Assign licenses to specific employees with emails  
✅ **Status Tracking** - Active, Inactive, Expired, Suspended states  
✅ **File Attachments** - Store URLs to certificates, documentation  
✅ **Custom Notes** - Add unlimited notes and details  
✅ **Search Everything** - Search across all license fields  
✅ **Advanced Filtering** - Filter by status, manufacturer, type  

### 🎨 **Modern Professional UI**

🎨 **Stunning Dashboard** - Gradient designs with smooth animations  
🎨 **Real-Time Stats** - Visual cards showing total, active, expiring licenses  
🎨 **Interactive Tables** - Sortable, filterable data tables  
🎨 **Modal Popups** - View, edit, delete without page reloads  
🎨 **Dark/Light Theme** - Toggle themes with persistent preferences  
🎨 **Color-Coded Status** - Instant visual identification  
🎨 **Responsive Design** - Perfect on desktop, tablet, mobile  
🎨 **Smooth Animations** - Professional transitions throughout  
🎨 **Copy to Clipboard** - One-click license key copying  
🎨 **Loading States** - Beautiful loading indicators  

### 🔔 **Smart Notifications**

📧 **Automated Emails** - Get notified before licenses expire  
📧 **Customizable Timing** - Set alert days (1-365) before expiry  
📧 **Beautiful Templates** - Professional HTML emails with branding  
📧 **Priority Levels** - Critical, High, Medium, Low urgency  
📧 **Multiple Recipients** - Send to different email addresses  
📧 **Test Email Function** - Verify configuration works  
📧 **Activity Alerts** - Notifications for additions, updates, deletions  

### 📊 **Advanced Analytics**

📈 **Visual Dashboard** - Overview of entire license portfolio  
📈 **Expiring Soon View** - Dedicated page for urgent licenses  
📈 **Priority Matrix** - See which licenses need immediate action  
📈 **Countdown Timers** - Real-time days until expiration  
📈 **Activity Logs** - Complete audit trail of all operations  
📈 **Usage Statistics** - Track license utilization  
📈 **Custom Reports** - Export filtered data for analysis  

### 💾 **Data Management**

💾 **CSV Export** - Download all licenses in Excel format  
💾 **Bulk Import** - Import hundreds of licenses from CSV  
💾 **Data Validation** - Automatic validation during import  
💾 **Backup Ready** - Export for backup or migration  
💾 **Duplicate Detection** - Avoid importing duplicates  
💾 **Error Handling** - Clear error messages for issues  

### 🔒 **Enterprise Security**

🔐 **WordPress Nonces** - CSRF attack protection  
🔐 **Role-Based Access** - Capability-based permissions  
🔐 **Input Sanitization** - All inputs sanitized and validated  
🔐 **SQL Injection Protection** - Prepared statements for queries  
🔐 **XSS Protection** - All outputs properly escaped  
🔐 **Activity Logging** - Track who made what changes  
🔐 **Secure File Handling** - Protected directories  

### ⚡ **Performance**

🚀 **Fast Loading** - Optimized queries and caching  
🚀 **AJAX Operations** - No page reloads for actions  
🚀 **Keyboard Shortcuts** - ESC, Ctrl+S shortcuts  
🚀 **Auto-Save Drafts** - Never lose your work  
🚀 **Form Validation** - Real-time validation  
🚀 **Accessible** - WCAG 2.1 compliant  

---

## 📸 Screenshots

### Professional Dashboard
![Dashboard](https://via.placeholder.com/800x400?text=License+Manager+Dashboard)
*Real-time statistics with visual cards and recent licenses overview*

### License Inventory
![All Licenses](https://via.placeholder.com/800x400?text=License+Inventory)
*Complete license listing with search, filters, and actions*

### License Details Modal
![License Details](https://via.placeholder.com/800x400?text=License+Details+Modal)
*Comprehensive license information in beautiful modal*

### Edit License Form
![Edit License](https://via.placeholder.com/800x400?text=Edit+License+Form)
*Clean form for updating license information*

### Expiring Licenses View
![Expiring Licenses](https://via.placeholder.com/800x400?text=Expiring+Licenses)
*Priority-based view of licenses requiring attention*

### Import/Export Interface
![Import Export](https://via.placeholder.com/800x400?text=Import+Export)
*Simple interface for bulk data operations*

---

## 💿 Installation

### Method 1: WordPress Admin (Recommended)

1. Download the plugin ZIP file
2. Navigate to **Plugins > Add New**
3. Click **Upload Plugin**
4. Choose the ZIP file
5. Click **Install Now**
6. Click **Activate**

### Method 2: Manual Installation

1. Download and extract the plugin
2. Upload the `license-manager-pro` folder to `/wp-content/plugins/`
3. Navigate to **Plugins** in WordPress admin
4. Find **License Manager Pro**
5. Click **Activate**

### Method 3: FTP Upload

1. Extract the plugin ZIP file
2. Connect via FTP to your WordPress installation
3. Upload folder to `/wp-content/plugins/`
4. Activate via WordPress admin panel

### Post-Installation Setup

1. Navigate to **License Manager** in admin menu
2. Go to **Settings**
3. Set **Notification Email** address
4. Configure **Alert Days** (default: 30)
5. Upload **Company Logo** (optional)
6. Click **Save Settings**
7. Ready to add licenses! 🎉

---

## 🚀 Quick Start

### Adding Your First License (2 Minutes)

1. **Navigate to License Manager**
   - Click **License Manager** in admin menu
   - Click **Add License** tab

2. **Fill Required Fields**
   ```
   License Key: XXXXX-XXXXX-XXXXX-XXXXX
   Product Name: Microsoft Office 365
   ```

3. **Add Optional Details**
   ```
   Manufacturer: Microsoft
   License Type: Subscription
   Expiry Date: 2025-12-31
   Seats: 10
   Status: Active
   ```

4. **Save**
   - Click **Add License**
   - Success! License is now tracked

### Quick Actions

**View All Licenses**: License Manager → All Licenses  
**Check Expiring**: License Manager → Expiring Soon  
**Export Data**: License Manager → Import/Export → Export  
**Configure Alerts**: License Manager → Settings  

---

## 📖 Usage Guide

### Managing Licenses

#### Adding a License

**Required Fields**:
- **License Key**: Your software license key
- **Product Name**: Name of the software

**Optional Fields**:
- **Manufacturer**: Software company
- **Brand**: Product family
- **Type**: Perpetual, Subscription, Trial, OEM, Volume, Educational
- **Purchase Date**: When purchased
- **Activated Date**: When activated
- **Expiry Date**: When expires (empty for perpetual)
- **Seats**: Number of user licenses
- **Users**: Comma-separated emails
- **Status**: Active, Inactive, Expired, Suspended
- **Files**: URLs to documentation
- **Notes**: Additional information

**Example**:
```
License Key: XXXXX-XXXXX-XXXXX-XXXXX-XXXXX
Product: Adobe Creative Cloud
Manufacturer: Adobe
Brand: Creative Cloud
Type: Subscription
Purchase Date: 2024-01-15
Activated: 2024-01-16
Expiry: 2025-01-15
Seats: 5
Users: john@company.com, jane@company.com
Status: Active
Files: https://account.adobe.com
Notes: Renewed annually
```

#### Editing a License

1. Go to **All Licenses**
2. Find the license
3. Click **Edit** ✏️ button
4. Modify fields in modal
5. Click **Update License**
6. Changes saved instantly

#### Deleting a License

1. Go to **All Licenses**
2. Find the license
3. Click **Delete** 🗑️ button
4. Confirm in dialog
5. License removed permanently

⚠️ **Warning**: Deletion cannot be undone!

#### Viewing License Details

1. Click **View** 👁️ on any license
2. Modal shows complete information
3. Copy license key with one click
4. See all dates and assignments

### Search & Filtering

**Search Functionality**:
- Product names
- Manufacturers
- Brands
- License keys
- User emails

**Available Filters**:
- Status (Active, Inactive, Expired, Suspended)
- Manufacturer
- License Type

**Examples**:
```
Search: "Microsoft" → Find all Microsoft products
Search: "john@company.com" → Find John's licenses
Filter: Status = Active → Show only active licenses
```

---

## 📧 Email Notifications

### Configuring Notifications

**Settings Path**: License Manager → Settings → Notification Settings

**Configuration Options**:
```
Notification Email: admin@yoursite.com
Alert Days: 30 (days before expiry)
```

**How It Works**:
1. Cron job runs daily (WordPress cron)
2. Checks for licenses expiring within alert days
3. Sends email to configured address
4. Logs notification in Activity Logs

### Email Template

**Includes**:
- Company logo (if configured)
- List of expiring licenses
- Days remaining for each
- License details
- Professional HTML formatting

### Testing Notifications

1. Go to **Settings**
2. Click **Send Test Notification**
3. Check configured email inbox
4. Verify email received

**Troubleshooting Email**:
- Install WP Mail SMTP plugin
- Check spam folder
- Verify WordPress can send emails
- Test with different email

---

## 💾 Import & Export

### Exporting Licenses

**When to Export**:
- Regular backups
- Data analysis
- Team sharing
- Migration

**How to Export**:
1. Navigate to **Import/Export** tab
2. Click **Export All Licenses**
3. CSV downloads automatically
4. Format: `licenses_export_YYYY-MM-DD_HH-MM-SS.csv`

**Export Includes**:
- All license fields
- Timestamps
- Complete history

### Importing Licenses

**CSV Format Required**:
```csv
ID,License Key,Product,Manufacturer,Brand,Type,Purchase Date,Activated Date,Expiry Date,Seats,Users,Status,Files,Notes,Created At
```

**Sample Row**:
```csv
1,XXXXX-XXXXX-XXXXX,Adobe Photoshop,Adobe,Creative Cloud,Subscription,2024-06-01,2024-06-02,2025-06-01,5,"user1@company.com, user2@company.com",active,https://account.adobe.com,Annual subscription,2024-06-01 10:30:00
```

**Import Steps**:
1. Prepare CSV file
2. Ensure UTF-8 encoding
3. Use date format: YYYY-MM-DD
4. Go to **Import/Export**
5. Click **Choose CSV File**
6. Select file
7. Click **Import Licenses**
8. Review results

**Import Tips**:
- ✅ Minimum: License Key, Product
- ✅ Comma-separate multiple users
- ✅ Leave dates empty for perpetual
- ✅ Status defaults to "active"
- ⚠️ Invalid rows skipped
- 💡 Export first to see format

---

## 📊 Analytics & Reporting

### Dashboard Overview

**Statistics Cards**:
1. **Total Licenses**: All-time count
2. **Active Licenses**: Currently active
3. **Expiring Soon**: Within alert days
4. **Expired**: Past expiry date

### Expiring Licenses View

**Priority Levels**:
- 🔴 **Expired**: Past expiry date
- 🟠 **Critical**: < 7 days
- 🟡 **High**: < 14 days
- 🟢 **Medium**: < 30 days

**Features**:
- Countdown timers
- Priority badges
- Quick actions
- Filtered view

### Activity Logs

**What's Logged**:
- License additions
- License updates
- License deletions
- Import operations
- Email notifications

**Log Details**:
- Action type
- Product/license affected
- User who performed action
- Timestamp

**Clearing Logs**:
1. Go to **Activity Logs**
2. Click **Clear Logs**
3. Confirm action
4. Logs permanently deleted

---

## 🎨 Customization

### Branding

**Settings Path**: License Manager → Settings → Branding

**Options**:
```
Company Logo URL: https://yoursite.com/logo.png
```

**Logo Usage**:
- Sidebar display
- Email notifications
- Header sections
- Recommended: 200x60 pixels
- Formats: JPG, PNG, SVG

### Theme Toggle

**Dark/Light Mode**:
- Toggle button in top-right
- Preference saved automatically
- Applies across all pages
- Smooth transition

### Color Customization

Edit `assets/css/admin-style.css`:

```css
:root {
  --primary-color: #6366f1;
  --primary-dark: #4f46e5;
  --success-color: #10b981;
  --warning-color: #f59e0b;
  --danger-color: #ef4444;
  --text-color: #1f2937;
  --border-color: #e5e7eb;
  --bg-color: #ffffff;
}
```

---

## 🔌 API & Hooks

### Available Actions

```php
// Plugin fully loaded
do_action('license_manager_pro_loaded');

// License added
do_action('lm_license_added', int $license_id, array $data);

// License updated
do_action('lm_license_updated', int $license_id, array $data);

// License deleted
do_action('lm_license_deleted', int $license_id);

// Licenses imported
do_action('lm_licenses_imported', int $count, array $licenses);

// Expiry notification sent
do_action('lm_expiry_notification_sent', array $licenses);
```

### Available Filters

```php
// Filter license data before save
$data = apply_filters('lm_before_save_license', array $data, int $license_id);

// Filter license after retrieval
$license = apply_filters('lm_after_get_license', object $license);

// Filter notification email content
$content = apply_filters('lm_notification_email_content', string $content, array $licenses);

// Filter email subject
$subject = apply_filters('lm_notification_email_subject', string $subject);

// Filter CSV export data
$licenses = apply_filters('lm_export_licenses', array $licenses);

// Filter alert days
$days = apply_filters('lm_notification_days', int $days);
```

### Example Hook Usage

```php
// Add custom action on license add
add_action('lm_license_added', function($license_id, $data) {
    // Sync with external system
    sync_to_crm($license_id, $data);
}, 10, 2);

// Modify email content
add_filter('lm_notification_email_content', function($content, $licenses) {
    $content .= "

Custom footer message.";
    return $content;
}, 10, 2);

// Add custom field
add_filter('lm_before_save_license', function($data, $license_id) {
    $data['custom_field'] = 'custom_value';
    return $data;
}, 10, 2);
```

---

## 🛠️ Requirements

### Minimum Requirements

| Component | Version |
|-----------|---------|
| WordPress | 5.0+ |
| PHP | 7.4+ |
| MySQL | 5.6+ |
| Memory | 64 MB+ |

### Recommended

| Component | Version |
|-----------|---------|
| WordPress | 6.0+ |
| PHP | 8.0+ |
| MySQL | 8.0+ |
| Memory | 128 MB+ |

### Browser Support

✅ Chrome 70+  
✅ Firefox 65+  
✅ Safari 12+  
✅ Edge 79+  
✅ Mobile browsers  

---

## 📁 File Structure

```
license-manager-pro/
├── license-manager-pro.php      # Main plugin file
├── uninstall.php                 # Cleanup on uninstall
├── README.md                     # Documentation
│
├── includes/                     # Core classes
│   ├── class-lm-core.php        # Utilities
│   ├── class-lm-database.php    # Database ops
│   └── class-lm-notifications.php # Email system
│
├── admin/                        # Admin functionality
│   ├── class-lm-admin.php       # Admin init
│   ├── class-lm-admin-pages.php # Page rendering
│   ├── class-lm-ajax.php        # AJAX handlers
│   └── views/                    # Templates
│       ├── dashboard.php
│       ├── all-licenses.php
│       ├── add-license.php
│       ├── edit-license.php
│       ├── expiring-licenses.php
│       ├── import-export.php
│       ├── settings.php
│       └── activity-logs.php
│
├── assets/                       # Frontend resources
│   ├── css/
│   │   └── admin-style.css      # Complete styling
│   ├── js/
│   │   └── admin-script.js      # Functionality
│   ├── images/
│   │   ├── icon.svg
│   │   └── banner.png
│   └── screenshots/
│
└── languages/                    # Translations
    └── license-manager.pot
```

---

## ❓ FAQs

### **Q: Is this plugin free?**
**A:** Yes! License Manager Pro is 100% free and open source under GPL v3.

### **Q: Does it work with multisite?**
**A:** Currently single-site only. Multisite support planned for v2.1.

### **Q: Can I customize the UI?**
**A:** Yes! Edit CSS files or use provided color variables. Dark/light themes included.

### **Q: Does it send email notifications?**
**A:** Yes! Automated expiry notifications with customizable timing and templates.

### **Q: Can I export my data?**
**A:** Yes! CSV export for all licenses, compatible with Excel and Google Sheets.

### **Q: Is it translation-ready?**
**A:** Yes! Fully translatable with included POT template file.

### **Q: Does it work on mobile?**
**A:** Yes! Fully responsive design optimized for all screen sizes.

### **Q: Can I track user assignments?**
**A:** Yes! Assign licenses to specific users via email addresses.

### **Q: Does it log activities?**
**A:** Yes! Complete audit trail of all license operations.

### **Q: Can I import bulk licenses?**
**A:** Yes! CSV import for hundreds of licenses at once.

---

## 🔧 Troubleshooting

### No Licenses Showing

**Solutions**:
1. Check database tables exist (Settings → System)
2. Deactivate and reactivate plugin
3. Check PHP error logs

### Email Notifications Not Working

**Solutions**:
1. Test email (Settings → Send Test)
2. Install WP Mail SMTP plugin
3. Check spam folder
4. Verify email address correct

### Import Fails

**Solutions**:
1. Check CSV format (see Import section)
2. Verify UTF-8 encoding
3. Check file size limits
4. Split large files

### Modal Not Opening

**Solutions**:
1. Check JavaScript console (F12)
2. Clear browser cache
3. Disable conflicting plugins
4. Switch to default theme

### Buttons Not Working

**Solutions**:
1. Check AJAX configuration
2. Clear caching plugins
3. Verify file permissions (644)
4. Check JavaScript errors

---

## 🛣️ Roadmap

### Version 2.1 (Planned - Q1 2026)
- [ ] Multisite network support
- [ ] Advanced reporting dashboard
- [ ] License renewal reminders
- [ ] Custom field builder
- [ ] API authentication for external apps

### Version 2.2 (Planned - Q2 2026)
- [ ] Integration with WooCommerce
- [ ] License key generator
- [ ] Automatic license validation
- [ ] Team collaboration features
- [ ] Mobile app (iOS/Android)

### Version 3.0 (Future)
- [ ] AI-powered license optimization
- [ ] Cost analysis and forecasting
- [ ] Vendor management portal
- [ ] Contract management
- [ ] Asset tagging system

---

## 🤝 Contributing

Contributions welcome! Here's how:

### Ways to Contribute

1. **Report Bugs** 🐛
   - Check existing issues
   - Provide detailed steps
   - Include screenshots

2. **Suggest Features** 💡
   - Explain use case
   - Describe expected behavior
   - Provide examples

3. **Submit Code** 👨‍💻
   - Fork repository
   - Create feature branch
   - Follow WordPress standards
   - Submit pull request

4. **Improve Docs** 📖
   - Fix typos
   - Add examples
   - Clarify instructions

5. **Translate** 🌍
   - Create .po/.mo files
   - Test thoroughly
   - Submit via PR

### Contribution Workflow

```bash
# Fork and clone
git clone https://github.com/YOUR-USERNAME/license-manager-pro.git

# Create branch
git checkout -b feature/amazing-feature

# Make changes
# ... code ...

# Commit
git commit -m "Add amazing feature"

# Push
git push origin feature/amazing-feature

# Open Pull Request on GitHub
```

### Code Guidelines

**WordPress Standards**:
```php
// ✅ Good
function lm_get_license($id) {
    global $wpdb;
    return $wpdb->get_row($wpdb->prepare(
        "SELECT * FROM {$wpdb->prefix}lm_licenses WHERE id = %d",
        $id
    ));
}

// ❌ Bad
function getLicense($id){
    return $wpdb->get_row("SELECT * FROM wp_lm_licenses WHERE id = $id");
}
```

---

## 👨‍💻 Credits

**Developed by:** Mohamed Houssem Eddine SAIGHI  
**Version:** 2.0.0  
**License:** GPL v3.0 or later  
**Requires:** WordPress 5.0+, PHP 7.4+  

### Technologies Used

- **WordPress** - CMS platform
- **jQuery** - JavaScript library
- **CSS Grid & Flexbox** - Modern layouts
- **PHP 7.4+** - Server-side logic
- **MySQL** - Database storage

### Special Thanks

- WordPress community
- All contributors and testers
- Users providing feedback
- Open source community

---

## 📄 License

**GNU General Public License v3.0 or later**

```
License Manager Pro - WordPress License Management Plugin
Copyright (C) 2025 Mohamed Houssem Eddine SAIGHI

This program is free software: you can redistribute it and/or modify
it under the terms of the GNU General Public License as published by
the Free Software Foundation, either version 3 of the License, or
(at your option) any later version.

This program is distributed in the hope that it will be useful,
but WITHOUT ANY WARRANTY; without even the implied warranty of
MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE. See the
GNU General Public License for more details.

You should have received a copy of the GNU General Public License
along with this program. If not, see <https://www.gnu.org/licenses/>.
```

**Read full license**: [GNU.org](https://www.gnu.org/licenses/gpl-3.0.html)

---

## 📞 Support

### Email Support
**Email**: support@yourcompany.com  
**Response**: 24-48 hours  

### Community Forum
**URL**: https://wordpress.org/support/plugin/license-manager-pro  

### Documentation
**URL**: https://yourcompany.com/docs/license-manager-pro  

### Bug Reports
**URL**: https://github.com/houssemdub/license-manager-pro/issues  

### Feature Requests
**URL**: https://github.com/houssemdub/license-manager-pro/discussions  

---

## 🌟 Show Your Support

If License Manager Pro helps you:

⭐ **Star on GitHub** - Click the star button  
✍️ **Write a Review** - Leave feedback on WordPress.org  
📢 **Share** - Tell colleagues and friends  
☕ **Buy Coffee** - Support development  
🤝 **Contribute** - See Contributing section  

---

## 🔗 Links

- **GitHub**: [https://github.com/houssemdub/license-manager-pro](https://github.com/houssemdub/license-manager-pro)
- **Issues**: [https://github.com/houssemdub/license-manager-pro/issues](https://github.com/houssemdub/license-manager-pro/issues)
- **WordPress.org**: Coming Soon
- **Documentation**: [https://yourcompany.com/docs](https://yourcompany.com/docs)

---

<div align="center">

**Made with ❤️ by [Mohamed Houssem Eddine SAIGHI](https://github.com/houssemdub)**

*Professional license management for WordPress*

⭐ **Star us on GitHub — it helps!** ⭐

[Report Bug](https://github.com/houssemdub/license-manager-pro/issues) · [Request Feature](https://github.com/houssemdub/license-manager-pro/discussions) · [Documentation](https://yourcompany.com/docs)

</div>

---

**Last Updated:** October 23, 2025  
**Plugin Version:** 2.0.0  
**WordPress Tested:** 6.8  
**PHP Version:** 7.4+

# License Manager Pro for WordPress

![License Manager Pro Banner](assets/images/banner.png)

[![Version](https://img.shields.io/badge/version-2.0.0-blue.svg)](https://github.com/yourusername/license-manager-pro/releases)
[![WordPress](https://img.shields.io/badge/WordPress-5.0%2B-brightgreen.svg)](https://wordpress.org/)
[![PHP](https://img.shields.io/badge/PHP-7.4%2B-purple.svg)](https://php.net/)
[![License: GPL v3](https://img.shields.io/badge/License-GPL%20v3-red.svg)](https://www.gnu.org/licenses/gpl-3.0)
[![PRs Welcome](https://img.shields.io/badge/PRs-welcome-brightgreen.svg)](http://makeapullrequest.com)

> **A professional enterprise-grade WordPress plugin for comprehensive software license management with a stunning modern UI, advanced analytics dashboard, and real-time tracking capabilities.**

Perfect for IT departments, software companies, agencies, and businesses that need to track and manage multiple software licenses across their organization.

---

## 📋 Table of Contents

- [Features](#-features)
- [Screenshots](#-screenshots)
- [Installation](#-installation)
- [Quick Start Guide](#-quick-start-guide)
- [Detailed Usage](#-detailed-usage)
- [Requirements](#-requirements)
- [File Structure](#-file-structure)
- [Configuration](#️-configuration)
- [Development](#-development)
- [Internationalization](#-internationalization)
- [Troubleshooting](#-troubleshooting)
- [Changelog](#-changelog)
- [Contributing](#-contributing)
- [License](#-license)
- [Support](#-support)

---

## 🌟 Features

### 📦 Comprehensive License Management

✅ **Centralized Storage** - Store unlimited software licenses with complete metadata  
✅ **License Types** - Perpetual, Subscription, Trial, OEM, Volume, Educational  
✅ **Multi-Field Tracking** - Product, Manufacturer, Brand, Type, Status, Dates  
✅ **Seat Management** - Track and manage user seat allocations  
✅ **User Assignment** - Assign licenses to specific employees with email tracking  
✅ **Status Management** - Active, Inactive, Expired, Suspended states  
✅ **Custom Notes** - Add unlimited notes and documentation for each license  
✅ **File Attachments** - Store URLs to license files, certificates, and documentation

### 🎨 Modern Professional UI

✨ **Beautiful Dashboard** - Clean interface with gradient designs and smooth animations  
✨ **Real-Time Statistics** - Visual cards showing total, active, expiring, and expired licenses  
✨ **Interactive Tables** - Sortable, filterable tables with intelligent search  
✨ **Modal Dialogs** - View, edit, and manage licenses without page reloads  
✨ **Dark/Light Theme** - Toggle between themes with automatic preference saving  
✨ **Responsive Design** - Flawless experience on desktop, tablet, and mobile  
✨ **Color-Coded Indicators** - Instant visual identification of license status  
✨ **Smooth Animations** - Professional transitions and micro-interactions

### 🔔 Smart Notification System

📧 **Automated Email Alerts** - Get notified before licenses expire  
📧 **Customizable Timing** - Set alert days (1-365) before expiry  
📧 **Beautiful Email Templates** - Professional HTML emails with your branding  
📧 **Priority Levels** - Critical, High, Medium, Low based on expiry urgency  
📧 **Multiple Recipients** - Send notifications to different email addresses  
📧 **Test Email Function** - Verify email configuration works correctly  
📧 **Activity Notifications** - Get alerts for license additions, updates, deletions

### 📊 Advanced Analytics & Reporting

📈 **Visual Dashboard** - At-a-glance overview of your license portfolio  
📈 **Expiring Soon View** - Dedicated dashboard for licenses needing attention  
📈 **Priority Matrix** - See which licenses require immediate action  
📈 **Countdown Timers** - Real-time display of days until expiration  
📈 **Activity Logs** - Complete audit trail of all license operations  
📈 **Usage Statistics** - Track license utilization and seat allocation  
📈 **Filtering & Search** - Advanced search across all license fields

### 📁 Data Management

💾 **CSV Export** - Download all licenses in Excel-compatible format  
💾 **Bulk Import** - Import hundreds of licenses from CSV files  
💾 **Data Validation** - Automatic validation during import process  
💾 **Backup Ready** - Export your data for backup or migration  
💾 **Duplicate Detection** - Avoid importing duplicate licenses  
💾 **Error Handling** - Clear error messages for import issues

### 🔒 Enterprise Security

🔐 **WordPress Nonces** - Protection against CSRF attacks  
🔐 **Capability Checks** - Role-based access control  
🔐 **Input Sanitization** - All user input is sanitized and validated  
🔐 **SQL Injection Protection** - Prepared statements for all queries  
🔐 **XSS Protection** - All output properly escaped  
🔐 **Activity Logging** - Track who made what changes when  
🔐 **Secure File Handling** - Protected upload directories

### ⚡ Performance & Usability

🚀 **Fast Loading** - Optimized database queries and caching  
🚀 **AJAX Operations** - No page reloads for common actions  
🚀 **Keyboard Shortcuts** - ESC to close modals, Ctrl+S to save  
🚀 **Copy to Clipboard** - One-click copying of license keys  
🚀 **Auto-Save Drafts** - Never lose your work while adding licenses  
🚀 **Form Validation** - Real-time validation with helpful error messages  
🚀 **Accessible** - WCAG 2.1 compliant for screen readers

---

## 📸 Screenshots

### 1. Professional Dashboard
![Dashboard Overview](assets/screenshots/dashboard.png)
*Modern dashboard with real-time statistics cards and recent licenses overview*

### 2. License Inventory
![All Licenses View](assets/screenshots/all-licenses.png)
*Complete license inventory with advanced search, filters, and action buttons*

### 3. License Details Modal
![License Details](assets/screenshots/license-details.png)
*Comprehensive license information displayed in a beautiful modal popup*

### 4. Edit License Form
![Edit License](assets/screenshots/edit-license.png)
*User-friendly form for updating license information*

### 5. Expiring Licenses Dashboard
![Expiring Licenses](assets/screenshots/expiring-licenses.png)
*Priority-based view highlighting licenses requiring immediate attention*

### 6. Add New License
![Add License Form](assets/screenshots/add-license.png)
*Clean, organized form for adding new licenses with validation*

### 7. Import/Export Interface
![Import Export](assets/screenshots/import-export.png)
*Simple interface for bulk importing and exporting license data*

### 8. Settings Panel
![Settings](assets/screenshots/settings.png)
*Configure notifications, branding, and system preferences*

---

## 🚀 Installation

### Method 1: Automatic Installation (Recommended)

1. Log in to your WordPress admin dashboard
2. Navigate to **Plugins** → **Add New**
3. Search for **"License Manager Pro"**
4. Click **Install Now** button
5. Click **Activate** once installation completes
6. Look for **License Manager** in the admin menu

### Method 2: Manual Installation via WordPress

1. Download the plugin ZIP file from the repository
2. Log in to your WordPress admin dashboard
3. Navigate to **Plugins** → **Add New**
4. Click **Upload Plugin** button at the top
5. Choose the downloaded ZIP file
6. Click **Install Now**
7. Click **Activate Plugin** after installation

### Method 3: Manual Installation via FTP

1. Download and extract the plugin ZIP file
2. Upload the `license-manager-pro` folder to `/wp-content/plugins/`
3. Log in to your WordPress admin dashboard
4. Navigate to **Plugins** → **Installed Plugins**
5. Find **License Manager Pro** and click **Activate**

### Post-Installation Setup

After activation, you'll see a welcome notice. Click **Configure Settings** or:

1. Navigate to **License Manager** → **Settings**
2. Set your **notification email address**
3. Configure **expiry alert days** (default: 30)
4. Upload your **company logo** (optional)
5. Click **Save Settings**
6. Ready to add your first license! 🎉

---

## 🎯 Quick Start Guide

### Adding Your First License (2 minutes)

1. **Navigate to Add License**
   - Click **License Manager** in the admin menu
   - Click **Add License** tab

2. **Fill Required Fields**
   - **License Key**: Your software license key/activation code
   - **Product Name**: Name of the software (e.g., "Microsoft Office 365")

3. **Add Optional Details** (Recommended)
   - Manufacturer: e.g., "Microsoft"
   - License Type: Select from dropdown
   - Expiry Date: When the license expires
   - Seats: Number of allowed users
   - Status: Active/Inactive/Expired

4. **Save**
   - Click **Add License** button
   - Success! Your license is now tracked

### Viewing All Licenses

1. Go to **License Manager** → **All Licenses**
2. Use the **search box** to find specific licenses
3. Apply **filters** for status or manufacturer
4. Click **View** 👁️ to see full details
5. Click **Edit** ✏️ to modify information
6. Click **Delete** 🗑️ to remove (with confirmation)

### Checking Expiring Licenses

1. Go to **License Manager** → **Expiring Soon**
2. See all licenses expiring within your configured timeframe
3. Licenses are color-coded by priority:
   - 🔴 **Red** = Expired
   - 🟠 **Orange** = Critical (< 7 days)
   - 🟡 **Yellow** = High priority (< 14 days)
   - 🟢 **Green** = Medium priority (< 30 days)

### Exporting Your Data

1. Go to **License Manager** → **Import/Export**
2. Click **Export All Licenses** button
3. CSV file downloads automatically
4. Open in Excel, Google Sheets, or any spreadsheet app

---

## 📖 Detailed Usage

### Managing Licenses

#### Adding a License

**Navigate**: License Manager → Add License

**Required Fields**:
- **License Key** - Your software license key or activation code
- **Product Name** - Name of the software product

**Optional Fields**:
- **Manufacturer** - Company that makes the software
- **Brand/Suite** - Product family (e.g., "Office", "Creative Cloud")
- **License Type** - Perpetual, Subscription, Trial, OEM, Volume, Educational
- **Purchase Date** - When you bought the license
- **Activated Date** - When the license was activated
- **Expiry Date** - When the license expires (leave empty for perpetual)
- **Number of Seats** - How many users can use this license
- **Assigned Users** - Email addresses of users (comma-separated)
- **Status** - Active, Inactive, Expired, Suspended
- **Files & Documentation** - URLs to license files, certificates, documentation
- **Notes** - Any additional information about the license

**Example**:
License Key: XXXXX-XXXXX-XXXXX-XXXXX-XXXXX
Product: Microsoft Office 365 Business
Manufacturer: Microsoft
Brand: Office
Type: Subscription
Purchase Date: 2024-01-15
Activated Date: 2024-01-16
Expiry Date: 2025-01-15
Seats: 10
Users: john@company.com, jane@company.com, bob@company.com
Status: Active
Files: https://portal.office.com/account/licenses
Notes: Renewed annually. Contact sales@microsoft.com for renewal.

text

#### Editing a License

1. Go to **All Licenses**
2. Find the license you want to edit
3. Click the **Edit** ✏️ button
4. Modify the fields in the modal form
5. Click **Update License**
6. Page refreshes with updated data

#### Deleting a License

1. Go to **All Licenses**
2. Find the license you want to delete
3. Click the **Delete** 🗑️ button
4. Confirm in the popup dialog
5. License is permanently removed
6. Action is logged in Activity Logs

⚠️ **Warning**: Deletion is permanent and cannot be undone!

#### Viewing License Details

1. Go to **All Licenses** or **Dashboard**
2. Click the **View** 👁️ button on any license
3. Modal popup shows complete information:
   - License key with copy button
   - All dates and status
   - Assigned users
   - Files and notes
   - Created and updated timestamps

### Search & Filtering

#### Using Search
The search function looks across:
- Product names
- Manufacturers
- Brands
- License keys
- Assigned user emails

#### Applying Filters
- **Status Filter**: Show only Active, Inactive, Expired, or Suspended
- **Manufacturer Filter**: Filter by specific manufacturer
- **Combine Filters**: Use search + filters together

#### Example Searches
- Type: `"Microsoft"` → Find all Microsoft products
- Type: `"john@company.com"` → Find licenses assigned to John
- Type: `"Office"` → Find Office-related licenses

### Import & Export

#### Exporting Licenses

**When to Export**:
- Regular backups
- Sharing data with team
- Analyzing in spreadsheets
- Migrating to another system

**How to Export**:
1. Navigate to **Import/Export** tab
2. Click **📤 Export All Licenses**
3. CSV file downloads automatically
4. Filename format: `licenses_export_YYYY-MM-DD_HH-MM-SS.csv`

**Export Includes**:
- All license fields
- Created and updated timestamps
- Complete history

#### Importing Licenses

**CSV Format Required**:
ID,License Key,Product,Manufacturer,Brand,Type,Purchase Date,Activated Date,Expiry Date,Seats,Users,Status,Files,Notes,Created At

text

**Sample CSV Row**:
1,XXXXX-XXXXX-XXXXX-XXXXX-XXXXX,Adobe Photoshop,Adobe,Creative Cloud,Subscription,2024-06-01,2024-06-02,2025-06-01,5,"user1@company.com, user2@company.com",active,"https://account.adobe.com","Annual subscription",2024-06-01 10:30:00

text

**Import Steps**:
1. Prepare your CSV file
2. Ensure UTF-8 encoding
3. Use date format: YYYY-MM-DD
4. Navigate to **Import/Export**
5. Click **📁 Choose CSV File**
6. Select your file
7. Click **📥 Import Licenses**
8. Review import results

**Import Tips**:
- ✅ Minimum required: License Key, Product
- ✅ Use commas for multiple users
- ✅ Leave dates empty for "never expires"
- ✅ Status defaults to "active" if not specified
- ⚠️ Invalid rows are skipped
- 💡 Export first to see correct format

### Email Notifications

#### Configuring Notifications

**Navigate**: License Manager → Settings → Notification Settings

**Configuration Options**:
- **Notification Email**: Where to send alerts
- **Alert Days**: Days before expiry to send notification (1-365)

**Email Template**:
Emails include:
- Your company logo (if configured)
- List of expiring licenses
- Days remaining for each
- License details
- Professional formatting

#### Testing Notifications

1. Go to **Settings**
2. Click **📧 Send Test Notification**
3. Check the configured email inbox
4. Verify email is received

**Troubleshooting Email**:
- Install WP Mail SMTP plugin
- Check spam folder
- Verify WordPress can send emails
- Test with different email address

### Activity Logs

**What's Logged**:
- License creations
- License updates
- License deletions
- Import operations
- Expiry alert notifications

**Viewing Logs**:
1. Navigate to **Activity Logs** tab
2. See chronological list of all activities
3. Each entry shows:
   - Action type
   - License/product affected
   - User who performed action
   - Timestamp

**Clearing Logs**:
1. Go to **Activity Logs**
2. Click **🗑️ Clear Logs** button
3. Confirm the action
4. All logs are permanently deleted

---

## 🛠️ Requirements

### Minimum Requirements

| Component | Version |
|-----------|---------|
| WordPress | 5.0+ |
| PHP | 7.4+ |
| MySQL | 5.6+ |
| Memory Limit | 64 MB+ |

### Recommended Requirements

| Component | Version |
|-----------|---------|
| WordPress | 6.0+ |
| PHP | 8.0+ |
| MySQL | 8.0+ |
| Memory Limit | 128 MB+ |

### PHP Extensions Required
- `mysqli` - Database connectivity
- `json` - Data processing
- `mbstring` - String handling

### Browser Compatibility
- ✅ Chrome 70+
- ✅ Firefox 65+
- ✅ Safari 12+
- ✅ Edge 79+
- ✅ Mobile browsers (iOS Safari, Chrome Mobile)

### Server Requirements
- HTTPS recommended (for security)
- Cron jobs enabled (for scheduled tasks)
- File permissions properly configured

---

## 📂 File Structure

license-manager-pro/
│
├── 📄 license-manager-pro.php # Main plugin file & bootstrap
├── 📄 uninstall.php # Cleanup on uninstall
├── 📄 README.md # This documentation file
│
├── 📁 includes/ # Core plugin classes
│ ├── class-lm-core.php # Core functionality & utilities
│ ├── class-lm-database.php # Database operations & queries
│ └── class-lm-notifications.php # Email notification system
│
├── 📁 admin/ # Admin area functionality
│ ├── class-lm-admin.php # Admin initialization & menus
│ ├── class-lm-admin-pages.php # Page rendering & controllers
│ ├── class-lm-ajax.php # AJAX request handlers
│ │
│ └── 📁 views/ # Template files (MVC pattern)
│ ├── sidebar.php # Navigation sidebar
│ ├── header.php # Page header
│ ├── modal.php # Modal container
│ ├── dashboard.php # Dashboard view
│ ├── all-licenses.php # License inventory
│ ├── add-license.php # Add license form
│ ├── edit-license.php # Edit license form
│ ├── license-details.php # License detail view
│ ├── expiring-licenses.php # Expiring licenses view
│ ├── import-export.php # Import/Export interface
│ ├── settings.php # Settings page
│ └── activity-logs.php # Activity logs view
│
├── 📁 assets/ # Frontend resources
│ ├── 📁 css/
│ │ └── admin-style.css # Complete styling (2000+ lines)
│ │
│ ├── 📁 js/
│ │ └── admin-script.js # Interactive functionality (450+ lines)
│ │
│ ├── 📁 images/
│ │ ├── icon.svg # Plugin icon
│ │ └── banner.png # Marketing banner
│ │
│ └── 📁 screenshots/ # Plugin screenshots
│ ├── dashboard.png
│ ├── all-licenses.png
│ ├── license-details.png
│ ├── edit-license.png
│ ├── expiring-licenses.png
│ ├── add-license.png
│ ├── import-export.png
│ └── settings.png
│
└── 📁 languages/ # Internationalization
└── license-manager-textdomain.pot # Translation template

text

### Key Files Explained

**Core Files**:
- `license-manager-pro.php` - Main plugin file, handles activation, initialization
- `includes/class-lm-core.php` - Utility functions, logging, common operations
- `includes/class-lm-database.php` - All database CRUD operations
- `includes/class-lm-notifications.php` - Email sending and templating

**Admin Files**:
- `admin/class-lm-admin.php` - Registers admin menus, enqueues assets
- `admin/class-lm-admin-pages.php` - Renders all admin pages
- `admin/class-lm-ajax.php` - Handles AJAX requests (view, edit, delete, etc.)

**View Templates**:
- All files in `admin/views/` - HTML templates with PHP logic
- Follow WordPress template hierarchy
- Use WordPress coding standards

**Assets**:
- `assets/css/admin-style.css` - Complete UI styling with CSS variables
- `assets/js/admin-script.js` - All JavaScript functionality
- Both files are heavily commented

---

## ⚙️ Configuration

### Email Notification Settings

**Access**: License Manager → Settings → Notification Settings

// Configure notification email
Notification Email: admin@yoursite.com

// Configure alert timing (days before expiry)
Alert Days: 30

text

**How Notifications Work**:
1. Cron job runs daily (WordPress cron)
2. Checks for licenses expiring within configured days
3. Sends email to configured address
4. Logs the notification in Activity Logs

### Branding Settings

**Access**: License Manager → Settings → Branding Settings

// Add your company logo
Company Logo URL: https://yoursite.com/logo.png

text

**Logo Usage**:
- Displayed in sidebar
- Included in email notifications
- Shown in header
- Recommended size: 200x60 pixels
- Supports: JPG, PNG, SVG

### System Settings

**Access**: License Manager → Settings → System Settings

**View Information**:
- Plugin version
- WordPress version
- PHP version
- Database tables status
- Active licenses count

**Maintenance Actions**:
- 📧 Send test notification email
- 🗑️ Clear all activity logs
- 🔄 Recreate database tables (troubleshooting)

### CSV Import Format

**Required Column Headers**:
ID, License Key, Product, Manufacturer, Brand, Type, Purchase Date, Activated Date, Expiry Date, Seats, Users, Status, Files, Notes, Created At

text

**Field Specifications**:

| Field | Type | Format | Required | Example |
|-------|------|--------|----------|---------|
| ID | Integer | Auto-increment | No | 1 |
| License Key | Text | Any format | Yes | XXXXX-XXXXX-XXXXX |
| Product | Text | Any | Yes | Microsoft Office 365 |
| Manufacturer | Text | Any | No | Microsoft |
| Brand | Text | Any | No | Office |
| Type | Text | Specific values | No | subscription |
| Purchase Date | Date | YYYY-MM-DD | No | 2024-01-15 |
| Activated Date | Date | YYYY-MM-DD | No | 2024-01-16 |
| Expiry Date | Date | YYYY-MM-DD | No | 2025-01-15 |
| Seats | Integer | Number | No | 10 |
| Users | Text | Comma-separated | No | user1@email.com, user2@email.com |
| Status | Text | active/inactive/expired/suspended | No | active |
| Files | Text | URLs | No | https://link.com |
| Notes | Text | Any | No | Renewal notes |
| Created At | Datetime | YYYY-MM-DD HH:MM:SS | No | 2024-01-15 10:30:00 |

**Valid License Types**:
- `perpetual` - Never expires
- `subscription` - Recurring payment
- `trial` - Temporary evaluation
- `oem` - Original Equipment Manufacturer
- `volume` - Bulk licensing
- `educational` - Academic license

---

## 🔧 Development

### Setting Up Local Development

Clone the repository
git clone https://github.com/yourusername/license-manager-pro.git

Navigate to your local WordPress installation
cd /path/to/wordpress/wp-content/plugins/

Create a symbolic link (or copy the files)
ln -s /path/to/license-manager-pro license-manager-pro

Activate in WordPress admin
Navigate to Plugins → Installed Plugins → Activate License Manager Pro
text

### Database Schema

#### Licenses Table: `wp_lm_licenses`

CREATE TABLE wp_lm_licenses (
id bigint(20) unsigned NOT NULL AUTO_INCREMENT,
license_key text NOT NULL,
product varchar(255) NOT NULL,
manufacturer varchar(255) DEFAULT '',
brand varchar(255) DEFAULT '',
type varchar(100) DEFAULT '',
purchase_date date DEFAULT NULL,
activated_date date DEFAULT NULL,
expiry_date date DEFAULT NULL,
seats int(11) DEFAULT 1,
users text DEFAULT '',
status varchar(50) DEFAULT 'active',
files text DEFAULT '',
notes text DEFAULT '',
created_at datetime DEFAULT CURRENT_TIMESTAMP,
updated_at datetime DEFAULT CURRENT_TIMESTAMP ON UPDATE CURRENT_TIMESTAMP,
PRIMARY KEY (id),
KEY idx_product (product(191)),
KEY idx_manufacturer (manufacturer(191)),
KEY idx_expiry (expiry_date),
KEY idx_status (status)
) ENGINE=InnoDB DEFAULT CHARSET=utf8mb4 COLLATE=utf8mb4_unicode_ci;

text

#### Activity Logs Table: `wp_lm_logs`

CREATE TABLE wp_lm_logs (
id bigint(20) unsigned NOT NULL AUTO_INCREMENT,
license_id bigint(20) unsigned DEFAULT NULL,
action varchar(100) NOT NULL,
description text DEFAULT '',
user_id bigint(20) unsigned NOT NULL,
created_at datetime DEFAULT CURRENT_TIMESTAMP,
PRIMARY KEY (id),
KEY idx_license_id (license_id),
KEY idx_action (action),
KEY idx_created_at (created_at)
) ENGINE=InnoDB DEFAULT CHARSET=utf8mb4 COLLATE=utf8mb4_unicode_ci;

text

### Available Hooks & Filters

#### Actions

// Fired when plugin is fully loaded
do_action('license_manager_pro_loaded');

// Fired after a license is added
do_action('lm_license_added', int $license_id, array $data);

// Fired after a license is updated
do_action('lm_license_updated', int $license_id, array $data);

// Fired after a license is deleted
do_action('lm_license_deleted', int $license_id);

// Fired when importing licenses
do_action('lm_licenses_imported', int $count, array $licenses);

// Fired when exporting licenses
do_action('lm_licenses_exported', int $count);

// Fired when expiry notification is sent
do_action('lm_expiry_notification_sent', array $licenses);

text

#### Filters

// Filter license data before saving
$data = apply_filters('lm_before_save_license', array $data, int $license_id);

// Filter license data after retrieval
$license = apply_filters('lm_after_get_license', object $license);

// Filter notification email content
$content = apply_filters('lm_notification_email_content', string $content, array $licenses);

// Filter notification email subject
$subject = apply_filters('lm_notification_email_subject', string $subject);

// Filter CSV export data
$licenses = apply_filters('lm_export_licenses', array $licenses);

// Filter days before expiry for notifications
$days = apply_filters('lm_notification_days', int $days);

// Filter email template
$template = apply_filters('lm_email_template', string $template, array $licenses);

text

### Example Hook Usage

// Example: Add custom data when a license is added
add_action('lm_license_added', function($license_id, $data) {
// Your custom code here
error_log("New license added: $license_id");

text
// Maybe sync with external system
sync_to_external_system($license_id, $data);
}, 10, 2);

// Example: Modify notification email content
add_filter('lm_notification_email_content', function($content, $licenses) {
// Add custom footer
$content .= "\n\nThis is a custom footer message.";
return $content;
}, 10, 2);

// Example: Add custom fields to license data
add_filter('lm_before_save_license', function($data, $license_id) {
// Add custom tracking field
$data['custom_field'] = 'custom_value';
return $data;
}, 10, 2);

text

### Extending the Plugin

Create a custom plugin that extends License Manager Pro:

<?php /* Plugin Name: License Manager Pro Extensions Description: Custom extensions for License Manager Pro Version: 1.0.0 */ // Wait for License Manager Pro to load add_action('license_manager_pro_loaded', function() { // Add custom menu item add_action('admin_menu', function() { add_submenu_page( 'license-manager-pro', 'Custom Report', 'Custom Report', 'manage_options', 'lm-custom-report', 'render_custom_report_page' ); }, 20); // Custom report function function render_custom_report_page() { echo '<div class="wrap">'; echo '<h1>Custom Report</h1>'; // Your custom report code echo '</div>'; } // Add custom notification logic add_action('lm_expiry_notification_sent', function($licenses) { // Send to Slack, Teams, or other services send_to_slack('Licenses expiring: ' . count($licenses)); }); }); ``` ### Coding Standards Follow WordPress Coding Standards: ``` // Class naming class LM_My_Extension {} // Function naming function lm_my_function() {} // Hook naming do_action('lm_my_custom_action'); // Variable naming $my_variable = 'value'; // Indentation: 4 spaces (no tabs) if ($condition) { // code here } // Braces on new line for functions function my_function() { // code } // Braces same line for control structures if ($condition) { // code } ``` --- ## 🌍 Internationalization License Manager Pro is fully translatable and ready for localization. ### Translation Files - **POT Template**: `languages/license-manager-textdomain.pot` - **Text Domain**: `license-manager` - **Domain Path**: `/languages` ### Translating the Plugin #### Using Poedit 1. Download and install [Poedit](https://poedit.net/) 2. Open the `.pot` file from `languages/` directory 3. Create a new translation for your language 4. Save as `license-manager-{locale}.po` 5. Poedit automatically generates `.mo` file 6. Upload both files to `/wp-content/languages/plugins/` #### Language File Naming ``` license-manager-{locale}.po license-manager-{locale}.mo ``` **Examples**: - French: `license-manager-fr_FR.po`, `license-manager-fr_FR.mo` - German: `license-manager-de_DE.po`, `license-manager-de_DE.mo` - Spanish: `license-manager-es_ES.po`, `license-manager-es_ES.mo` ### Translation Functions Used ``` // Simple translation __('Text to translate', 'license-manager') // Translation with echo _e('Text to translate', 'license-manager') // Plural forms _n('1 license', '%s licenses', $count, 'license-manager') // Context-specific translation _x('Settings', 'menu item', 'license-manager') // Escaped translation esc_html__('Text to translate', 'license-manager') ``` ### Contributing Translations We welcome translation contributions! 1. Fork the repository 2. Create your translation files 3. Test thoroughly in your language 4. Submit a pull request with: - `.po` and `.mo` files - Language code in filename - Your name in contributors --- ## 🐛 Troubleshooting ### Common Issues & Solutions #### Issue: No Licenses Showing **Symptoms**: All Licenses page shows "No Licenses Found" even though you added licenses **Solutions**: 1. Check if database tables exist: ``` Go to: Settings → System Settings Check: Database Tables status ``` 2. Recreate tables: ``` Go to: wp-admin → Plugins Deactivate → Reactivate the plugin ``` 3. Check PHP error logs: ``` Enable WP_DEBUG in wp-config.php Check error logs for SQL errors ``` --- #### Issue: Email Notifications Not Working **Symptoms**: Not receiving expiry notification emails **Solutions**: 1. Test email functionality: ``` Go to: Settings → Maintenance Actions Click: Send Test Notification Check inbox and spam folder ``` 2. Install WP Mail SMTP plugin: ``` Plugins → Add New Search: WP Mail SMTP Install and configure with SMTP details ``` 3. Check notification settings: ``` Settings → Notification Settings Verify email address is correct Test with different email ``` --- #### Issue: Import Fails **Symptoms**: CSV import shows errors or imports 0 licenses **Solutions**: 1. Check CSV format: ``` First row must be headers Required: License Key, Product Date format: YYYY-MM-DD ``` 2. Verify encoding: ``` Save CSV as UTF-8 encoding Use Excel: Save As → CSV UTF-8 ``` 3. Check file size: ``` PHP upload_max_filesize might be too small Split large files into smaller batches ``` --- #### Issue: Modal/Popup Not Opening **Symptoms**: Clicking View/Edit button does nothing **Solutions**: 1. Check JavaScript console: ``` Press F12 → Console tab Look for JavaScript errors ``` 2. Clear browser cache: ``` Ctrl+Shift+Delete (Chrome/Firefox) Clear cached files and reload ``` 3. Check for JavaScript conflicts: ``` Disable other plugins temporarily Switch to default WordPress theme Test if modal works ``` --- #### Issue: Buttons Not Working **Symptoms**: View, Edit, Delete buttons don't respond **Solutions**: 1. Check AJAX configuration: ``` View page source Look for: var lm_ajax = {...} Verify nonce is present ``` 2. Clear plugin cache: ``` If using caching plugin (WP Super Cache, etc.) Clear all caches Reload the page ``` 3. Check file permissions: ``` Verify admin-script.js is loading Check file permissions (644 for files) ``` --- #### Issue: Database Errors **Symptoms**: White screen or "Database error" messages **Solutions**: 1. Check database connection: ``` Verify wp-config.php database credentials Test MySQL connection ``` 2. Repair database tables: ``` phpMyAdmin → wp_lm_licenses Run: REPAIR TABLE ``` 3. Increase memory limit: ``` wp-config.php: define('WP_MEMORY_LIMIT', '256M'); ``` --- #### Issue: Plugin Conflicts **Symptoms**: Site breaks after activating plugin **Solutions**: 1. Identify conflicting plugin: ``` Deactivate all plugins Reactivate one by one Test after each activation ``` 2. Check theme compatibility: ``` Switch to Twenty Twenty-Four theme Test if issue persists ``` 3. Enable debug mode: ``` wp-config.php: define('WP_DEBUG', true); define('WP_DEBUG_LOG', true); Check debug.log file ``` --- ### Getting Help If you can't resolve the issue: 1. **Check Documentation**: Read this README thoroughly 2. **Search Issues**: Check GitHub issues for similar problems 3. **Gather Information**: - WordPress version - PHP version - Plugin version - Error messages - Steps to reproduce 4. **Contact Support**: See [Support](#-support) section below --- ## 📝 Changelog ### Version 2.0.0 - October 23, 2025 #### 🎉 Major Release - Complete Redesign **New Features**: - ✨ Complete UI redesign with modern professional interface - ✨ Enhanced modal popups with edit functionality - ✨ Advanced filtering and search capabilities - ✨ Dark/light theme toggle with persistent preferences - ✨ Copy-to-clipboard functionality for license keys - ✨ Keyboard shortcuts (ESC, Ctrl+S, Ctrl+K) - ✨ Form draft auto-save functionality - ✨ Real-time form validation - ✨ Activity logging system - ✨ Priority-based expiring licenses view **Improvements**: - 🚀 Improved mobile responsiveness - 🚀 Better error handling and user feedback - 🚀 Optimized database queries - 🚀 Enhanced security with nonce verification - 🚀 Improved accessibility (WCAG 2.1 compliant) - 🚀 Better code organization (MVC pattern) - 🚀 Comprehensive inline documentation **UI Enhancements**: - 🎨 Gradient designs and smooth animations - 🎨 Color-coded status indicators - 🎨 Professional email templates with branding - 🎨 Interactive statistics cards - 🎨 Hover effects and micro-interactions - 🎨 Loading states and progress indicators **Technical**: - 💻 2000+ lines of professional CSS - 💻 450+ lines of optimized JavaScript - 💻 AJAX-powered operations - 💻 REST API endpoints for integrations - 💻 Comprehensive hooks and filters - 💻 Translation-ready with POT file **Bug Fixes**: - 🐛 Fixed modal transparency issues - 🐛 Resolved CSV export header errors - 🐛 Fixed JavaScript syntax errors - 🐛 Corrected database query preparation - 🐛 Fixed AJAX nonce verification - 🐛 Resolved mobile layout issues --- ### Version 1.0.0 - Initial Release **Core Features**: - Basic license management (Add, View, Delete) - Simple email notifications - CSV import/export functionality - Basic statistics dashboard - Activity logging --- ## 🤝 Contributing We love contributions! Whether it's bug reports, feature requests, or code contributions, all are welcome. ### Ways to Contribute 1. **Report Bugs** 🐛 - Check existing issues first - Provide detailed steps to reproduce - Include error messages and screenshots - Mention your environment (WP version, PHP version) 2. **Suggest Features** 💡 - Check if already suggested - Explain the use case - Describe expected behavior - Provide examples if possible 3. **Submit Code** 👨‍💻 - Fork the repository - Create a feature branch - Write clean, documented code - Follow WordPress coding standards - Submit a pull request 4. **Improve Documentation** 📖 - Fix typos - Add examples - Clarify instructions - Translate to other languages 5. **Help Others** 🙋 - Answer questions in issues - Help troubleshoot problems - Share your use cases - Write tutorials ### Contribution Workflow 1. **Fork the Repository** ``` # Click Fork button on GitHub # Clone your fork git clone https://github.com/YOUR-USERNAME/license-manager-pro.git cd license-manager-pro ``` 2. **Create a Feature Branch** ``` git checkout -b feature/amazing-feature # or git checkout -b bugfix/fix-issue-123 ``` 3. **Make Your Changes** - Write clean, readable code - Add comments where needed - Follow existing code style - Test thoroughly 4. **Commit Your Changes** ``` git add . git commit -m "Add amazing feature" # Good commit message examples: # "Add edit button functionality to license list" # "Fix: Modal not closing on ESC key" # "Improve: Optimize database queries for better performance" # "Docs: Add troubleshooting section to README" ``` 5. **Push to Your Fork** ``` git push origin feature/amazing-feature ``` 6. **Open a Pull Request** - Go to your fork on GitHub - Click "New Pull Request" - Describe your changes - Reference any related issues - Wait for review ### Code Guidelines **WordPress Coding Standards**: ``` // ✅ Good function lm_get_license($id) { global $wpdb; return $wpdb->get_row($wpdb->prepare( "SELECT * FROM {$wpdb->prefix}lm_licenses WHERE id = %d", $id )); } // ❌ Bad function getLicense($id){ global $wpdb; return $wpdb->get_row("SELECT * FROM wp_lm_licenses WHERE id = $id"); } ``` **JavaScript Standards**: ``` // ✅ Good openModal: function(e) { e.preventDefault(); const licenseId = $(e.currentTarget).data('id'); if (!licenseId) { this.showNotification('Invalid ID', 'error'); return; } // Rest of code... } // ❌ Bad openModal:function(e){ var id=$(e.currentTarget).data('id') // No validation, poor formatting } ``` **CSS Guidelines**: ``` /* ✅ Good */ .lm-modal { position: fixed; top: 0; left: 0; width: 100%; height: 100%; z-index: 999999; } /* ❌ Bad */ .lm-modal{position:fixed;top:0;left:0;width:100%;height:100%;z-index:999999} ``` ### Pull Request Checklist Before submitting your PR, ensure: - [ ] Code follows WordPress coding standards - [ ] All functions are documented with PHPDoc - [ ] JavaScript includes comments for complex logic - [ ] CSS is organized and uses existing variables - [ ] No console.log() or debug code left in - [ ] Tested on latest WordPress version - [ ] Tested on PHP 7.4 and 8.0+ - [ ] No security vulnerabilities introduced - [ ] All user inputs are sanitized - [ ] All outputs are escaped - [ ] Database queries use prepared statements - [ ] Works with dark/light theme - [ ] Mobile responsive - [ ] No JavaScript errors in console - [ ] Backward compatible (if applicable) ### Reporting Security Issues ⚠️ **Please do not report security vulnerabilities publicly!** If you discover a security issue: 1. Email: security@yourcompany.com 2. Include detailed description 3. Steps to reproduce 4. Potential impact 5. Suggested fix (if any) We'll respond within 48 hours and work with you on a fix. --- ## 📄 License **License Manager Pro** is licensed under the **GNU General Public License v3.0 or later**. ### What This Means ✅ **You Can**: - Use the plugin commercially - Modify the source code - Distribute copies - Use privately without publishing changes - Patent use granted ❌ **You Must**: - Include copyright notice - State changes made to code - Disclose source code - Use same license for derivatives - Include original license text ### Full License Text ``` License Manager Pro - WordPress License Management Plugin Copyright (C) 2025 Your Company This program is free software: you can redistribute it and/or modify it under the terms of the GNU General Public License as published by the Free Software Foundation, either version 3 of the License, or (at your option) any later version. This program is distributed in the hope that it will be useful, but WITHOUT ANY WARRANTY; without even the implied warranty of MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE. See the GNU General Public License for more details. You should have received a copy of the GNU General Public License along with this program. If not, see <https://www.gnu.org/licenses/>. ``` **Read full license**: [LICENSE](LICENSE) file or [GNU.org](https://www.gnu.org/licenses/gpl-3.0.html) --- ## 📞 Support Need help? We're here for you! ### 📧 Email Support **Email**: support@yourcompany.com **Response Time**: Within 24-48 hours **Best For**: Technical issues, bugs, feature requests ### 💬 Community Forum **URL**: https://wordpress.org/support/plugin/license-manager-pro **Best For**: General questions, usage help, tips ### 📖 Documentation **URL**: https://yourcompany.com/docs/license-manager-pro **Includes**: Video tutorials, guides, FAQs ### 🐛 Bug Reports **URL**: https://github.com/yourusername/license-manager-pro/issues **Best For**: Reporting bugs with detailed info ### 💡 Feature Requests **URL**: https://github.com/yourusername/license-manager-pro/discussions **Best For**: Suggesting new features, improvements ### 🚀 Premium Support **URL**: https://yourcompany.com/premium-support **Includes**: Priority support, custom development, dedicated help ### Support Hours - Monday - Friday: 9:00 AM - 6:00 PM EST - Saturday - Sunday: Closed - Response time: 24-48 hours on business days --- ## 🌟 Show Your Support If you find **License Manager Pro** helpful, please consider: ### ⭐ Star on GitHub Click the ⭐ Star button at the top of this repository ### ✍️ Write a Review Leave a review on [WordPress.org](https://wordpress.org/support/plugin/license-manager-pro/reviews/) ### 📢 Share with Others - Tweet about it - Blog about it - Share in Facebook groups - Recommend to colleagues ### ☕ Buy Us a Coffee Support ongoing development: [Donate](https://yourcompany.com/donate) ### 🤝 Contribute See [Contributing](#-contributing) section above --- ## 🙏 Acknowledgments ### Built With - [WordPress](https://wordpress.org/) - The best CMS platform - [jQuery](https://jquery.com/) - JavaScript library - [CSS Grid & Flexbox](https://css-tricks.com/) - Modern layouts - [Font Awesome](https://fontawesome.com/) - Icon toolkit (optional) ### Inspired By - WordPress plugin best practices - Modern admin dashboard designs - User feedback and feature requests - Real-world license management needs ### Special Thanks - WordPress community for coding standards - All contributors and testers - Users who provided feedback - Open source community --- ## 📱 Connect With Us - 🌐 Website: https://yourcompany.com - 🐦 Twitter: [@yourcompany](https://twitter.com/yourcompany) - 📘 Facebook: [YourCompany](https://facebook.com/yourcompany) - 💼 LinkedIn: [Your Company](https://linkedin.com/company/yourcompany) - 📧 Email: hello@yourcompany.com --- ## 📊 Project Stats ![GitHub last commit](https://img.shields.io/github/last-commit/yourusername/license-manager-pro) ![GitHub issues](https://img.shields.io/github/issues/yourusername/license-manager-pro) ![GitHub stars](https://img.shields.io/github/stars/yourusername/license-manager-pro) ![GitHub forks](https://img.shields.io/github/forks/yourusername/license-manager-pro) ![GitHub downloads](https://img.shields.io/github/downloads/yourusername/license-manager-pro/total) --- <div align="center"> **Made with ❤️ for the WordPress Community** ⭐ **Star us on GitHub — it helps!** ⭐ [Report Bug](https://github.com/yourusername/license-manager-pro/issues) · [Request Feature](https://github.com/yourusername/license-manager-pro/discussions) · [Documentation](https://yourcompany.com/docs) </div> --- **Last Updated**: October 23, 2025 **Plugin Version**: 2.0.0 **WordPress Compatibility**: 5.0+ **Tested Up To**: 6.8 **PHP Version**: 7.4+ ```

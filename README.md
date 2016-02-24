oidejapan-frontend-ui
============

Mockups for Oide Japan platform.

Platform requires three separate interfaces for admin, business, and tourist users, each with differing levels of access. Consider as a PaaS where the platform itself is managed by the admin, the service is managed by the business, and the content provided by the service is consumed by the tourist. Planned services include Japanese-English translation via Gengo API, CMS/web hosting via LocomotiveCMS, and in-house eCommerce system.

### Admin

UI for internal back-office management, used to manage business accounts/users, tourist-facing site, and platform settings. Dark interface for clean separation from business and tourist interfaces.

Components/views:
- Profile: admin role user management
- Session: admin role session management
- Business: CRUD on business users
- Accounting: payment management for PaaS subscriptions
- Translation: CRUD on translation jobs
- Content: CRUD and management on hosted business websites (LocomotiveCMS API)
- Notification: internal admin-business notification system
- Experience: CRUD on business product _(not mocked up)_
- Group: CRUD on tourist purchases of business product _(not mocked up)_

### Business

UI for business role users to manage business profile, images, information, products, and other business data. Medium-tone interface for ease of use and distinction from tourist interface.

Components/views:
- Profile: business role user management
- Session: business role session management
- Business: CRUD on business information
- Accounting: payment management for PaaS subscriptions
- Translation: CRUD on translation jobs
- Content: CRUD and management for hosted website
- Notification: internal admin-business and business-tourist notification system
- Experience: CRUD on business product _(not mocked up)_
- Group: CRUD on tourist purchases of business product _(not mocked up)_

### Tourist

UI for tourist role users to search for business information and browse and purchase business products. Bright interface to complement high amount of visual content.

Components/views:
- Home: landing page
- Session: tourist role session management
- Profile: tourist role user management
- Browse: views for browsing business products
- Business: views for browsing business information
- Group: views for purchasing business product
- Trip: views for managing purchased products

---

Tools: Adobe Illustrator, Workflowy


# Update 9.0.0 - 4 May, 2022
 - Implemented the ability to enable/disable auto language detection via the admin panel.
 - Implemented the ability to set a different logo base on the theme style (dark or light).
 - Implemented the ability to set a different logo for emails.
 - Implemented the ability to reset vcard statistics.
 - Implemented RTL support for emails & improved the email templates looks.
 - Implemented the ability to create multi-language pages from the admin panel.
 - Implemented an anti-phishing system code for emails sent out to users by the system.
 - Implemented the TikTok pixel in the Pixels system.
 - Contact form, you can now reply-to via your email client directly via the sent email.
 - Resend activation page will now be disabled if the email confirmation setting is disabled.
 - Reworked and improved the Sitemap to include more pages, dynamically.
 - Improved the pages resources center UI & fixed small bugs.
 - Reworked and improved the language & dark mode switcher.
 - Fixed Mollie annual payments not processing correctly.
 - Fixed reset password not working for some particular emails & not logging the user in after the password change.
 - Fixed bug when logging in with a custom language set, yet the user has another language to his account.
 - Fixed admin impersonation of user logout not working properly.

# Update 8.0.0 - 29 March, 2022
 - Implemented the Teams system & released the 👨‍💻 Teams Plugin.
 - Implemented cookie consent logging feature to store proof of given consent.
 - Implemented cookie consent logging export to CSV.
 - Implemented cookie consent on vcard pages as well.
 - Implemented cookie consent settings link in the footer, so that people can change their given consent at all times.
 - Implemented the ability to generate discount/redeemable codes in bulk via the admin panel.
 - Implemented new dedicated code redeeming page.
 - Implemented Paddle payment gateway for one-time payments.
 - All user sessions will be logged out if the account changes password (security improvement).
 - Fixed language preference not persisting when doing certain actions while logged in.
 - Fixed language preference of a user being reset when re-logging in.

# Update 7.0.0 - 4 March, 2022
 - Implemented Cookie Consent functionality, highly configurable via the admin panel and translation system.
 - Implemented Discord login functionality, configurable via the admin panel.
 - Fixed payment generation issue in some special cases for a few payment gateways.
 - Multiple visual & functional improvements, bugfixes.

# Update 6.1.0 - 16 February, 2022
 - Implemented the ability to enable/disable a language via the admin panel.
 - Implemented the ability to filter translated, non translated and all strings when editing a language via the admin panel.
 - Fixed various new translation system issues.
 - Small other visual improvements.
 - Product rebranding from 22Vcard to 66vcard.

# Update 6.0.0 - 6 February, 2022
 - Fully reworked the Languages & Translations system for much better performance, handling and usability.
 - Implemented the ability to edit and translate Languages from the admin panel.
 - Implemented Crypto.com one-time payment gateway.

# Update 5.0.0 - 22 January, 2022
 - Implemented user registration blacklist by country.
 - Emojis in URL alias are now allowed for Vcards.
 - Reworked the admin panel footer (added language switcher + theme switcher).
 - Reworked the footer of the whole app.
 - Reworked the plugin system so plugins won't lose their state anymore when updating.
 - Improved UI for all tables on mobile.
 - Improved UX workflow bug when skipping trial & introducing billing details.
 - Improved responsiveness for account payments & logs pages.
 - Improved color contrast in Dark mode.
 - Fixed UI alignment issues on mobile.
 - Fixed payment generation bug when using discount codes in some cases.
 - Fixed admin panel settings UI menu bug.
 - Fixed caching problem regarding Pixels when deleting pixels.
 - Fixed & improved many other small UI issues.

# Update 4.0.0 - 2 January, 2022
 - Implemented a new Directory page for vcard pages.
 - Improved the UX of impersonating a user, as an admin.
 - Other small yet many improvements of the whole system.

# Update 3.0.0 - 15 December, 2021
 - Implemented the ability to set vcard blocks to open in a new page or not.
 - Implemented a built-in Contact form page (can be enabled from the admin panel -> website settings -> email notifications).
 - Implemented the ability to skip a trial when paying for a plan.
 - Implemented the ability to block registrations from a particular email domain, from the admin panel.
 - Implemented the ability to purge the cache from the admin panel.
 - Implemented the ability to set the default data order (asc, desc) the admin panel.
 - Implemented the ability to set the default pagination results the admin panel.
 - Implemented the ability to set a custom 404 page from the admin panel.
 - Implemented the ability to also export to PDF/print data from tables in the admin panel.
 - Admin Codes - Implemented the ability to paginate, filter, export data.
 - Admin Taxes - Implemented the ability to paginate, filter, export data.
 - Improved the admin panel -> website settings -> main fields, separated them for more clarity.
 - Improved the file upload error handling.
 - Now reCaptcha and hCaptcha will follow the language that the user currently uses.
 - Fixed a few bugs related to the system.

# Update 2.0.0 - 20 November, 2021
 - Implemented Yookassa one-time payments system.
 - Implemented PayU one-time payments system.
 - Implemented RazorPay one-time & recurring payments system.
 - Implemented Mollie one-time & recurring payments system.
 - Implemented Paystack one-time & recurring payments system.
 - Implemented an Auto Cleanup functionality for old, inactive users. Can be activated and configured in the admin panel.
 - Implemented email notifications for old & soon-to-be-deleted users, if the Auto Cleanup functionality is enabled.
 - Implemented the ability to see the list of referred users of a particular user from the admin panel.
 - Implemented the ability to set custom css and custom javascript for vcard pages only from the admin panel.

# Update 1.4.0 - 5 November, 2021
 - Implemented the ability to set a custom First Name, Last Name, Company name, Job title & Birthday for each Vcard.
 - Small improvements to the QR code generator for each vcard as well.
 - Updated all composer dependencies to their latest version.
 - Small improvements to the API documentation.

# Update 1.3.0 - 21 October, 2021
 - Dashboard vcards fix ordering, added logo image to the table for better looks.
 - Fixed admin update page not working.
 - Fixed address block not pointing to the proper google maps URL in some cases.
 - Fixed vcard export problems caused by certain web-host settings.
 - Fixed login, register pages visual bug.
 - Fixed vcard page icons not properly displaying in safari.

# Update 1.2.0 - 17 October, 2021
 - Implemented & developed the new Image Optimizer Plugin -> Image Optimizer Plugin
 - Fixed vcard blocks reordering problem.
 - Vcard logos will now only be exported to the .vcf file if they are under 750KB (they can't be processed if larger).
 - Fixed vcard blocks icon/text alignment issues.
 - Fixed vcard blocks text not wrapping properly.

# Update 1.1.0 - 15 October, 2021
 - Implemented the ability to enable/disable the QR code builder on a per-plan basis, via the admin panel.
 - Fixed vcard blocks reordering problem.
 - Fixed vcard blocks caching related problem.
 - Fixed vcard blocks enable/disable functionality.
 - Fixed admin not being able to delete Vcards blocks.

# Initial release - 14 October, 2021

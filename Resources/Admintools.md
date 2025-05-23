# General settings

You can customize the top menu items of home page, new products, search, my account, blog, forums and contact us and on the footer items you can display sitemap, contact us, search, news, blog, forums, recently viewed products, compare products list, new producs, my account, orders, addresses, shopping card, wishlist and apply for vendor account.

In the sitemap area you can enable the sitemap, change page size, include categories, include manufacturers, include products, tags, topics, blog posts and news items.

Some SEO options also (search engine optimization), option to toggle HTML minification (removes bloat such as comments and whitespace so page loads faster).

In security theres options to add specific IP addresses who can access the backend along with an encryption key and a honeypot.

Whats a honeypot I wonder.

Hm, so it adds invisible fields that normal users wont see but automated bots and similar will fill out and thus trigger antispam, clever thing.

Some options for the robots.txt file, which is a file that adds directives for bots what pages they may or may not access. Though it's a double edged sword considering the parts you assign as sensitive will be more interesting for evil bots to check out.

Ugh, you can enable CAPTCHA, thats horrible, but could be needed sometimes I guess.

Pdf settings, can add a logo for the order invoice, manage the footer text left and right column, change size between A4 and letter, can block access to print pdf invoices for pending orders.

"Sets the CLDR pattern for localization of client-side validation according to the current culture"

No idea about this one, lets find out what it is.

CLDR => Common Locale Data Repository
- a standard to like set number formats, dates etc based on the users language preferences. So 15.5 turns into 15,5 if swedish is active.

The bottom part you can add some custom HTML for the header and the footer and switch between HTML and a rich editor for message templates.

# Customer settings

Select registration method
- Standard => register and become registered
- Email Validation => need to validate mail before becoming registered
- Admin approval => need to await admin approval to become registered
- Disabled => Can't register at all

Get notified when a new customer has registered

Require registration or not for buying downloadable products

Allow customers to check gift card balance, if toggled requires CAPTCHA to prevent brute force

Allow customers to select time zone

Default time zone settings

Allow customers to remove associations
- external authentication => logging into the webshop using third party account like google account login or github or w/e, also called social login or external login
- removing associations will remove the google login etc

Password settings
- minimum and maximum length
- require lowercase, uppercase, alphanumeric, digit, unduplicated password numbers
- password format (hashed, encrypted or clear)
- password lifetime in days, how long recovery link is valid, maximum login failures, lockout time if failed login, option to force entering email twice, option to force multi-factor auth

Account
- enable username (instead of email)
- customer name format (first name, full name, username or email)
- validate phone number
- allow customer to upload avatars
- hide/show 'Downloadable products' tab
- hide/show 'back in stock subscriptions' tab
- hide/show newsletter box
- allow to unsubscribe from newsletter
- store last visited page
- store ip addresses (could be regulated due gdpr stuff in EU or CCPA in california and such)

Profile
- allow viewing of customer profiles (so customers can watch other customers profiles)
- show customers location and/or join date

Customer form fields (during registration of new user)
- gender enabled (male, female)
- neutral option enabled (neutral gender)
- first name, last name, company (enabled or not and also required or not)
- DOB, street address, street address 2, zip, city, region, country, phone number, fax number, accept privacy policy, newsletter (enabled or not)
- should newsletter be ticked by default
- can manage additional attributes from a table

Address form fields (during checkout)
- company, streed address, street address 2, zip, city, phone number, fax number (enabled/required)
- region, country, state/province (enabled)
- default country
- can also manage additional attributes

# Order settings

Checkout
- disable checkout (temporary closed store checkout)
- toggle anonymous checkout (can buy without account)
- use one page checkout
- order totals on payment info tab (for one page checkout)
- terms of service on shopping cart page to accept or decline
- terms of service on confirm order page
- disable 'billing address' step
- disable 'order completed' page
- display 'pickup in store' on 'shipping method' page

Order totals
- minimum sub-total amount in usd
- calculate 'min order sub-total amount' including tax
- min order total amounts (quantity)
- auto update order totals (beta testing, its for adjusting an order in admin area)

Common
- Order ID (starting point)
- order number mask (like basing it on the order date or user ID or w/e)
- is re-order allowed (button to purchase the same order as last time)
- complete order when delivered (changes status from shipped to delivered, otherwise once shipped its enough)
- Export orders with products (ex 1001, John Doe, 2025-05-23, Red T-Shirt, TS-RED, 2, 25.00 vs 1001, John Doe, 2025-05-23, 100.00, Complete)
- Allow admins to buy "Call for price" products (if store admins can add products without listed price to the cart of people and set a price for it)
- show product thumbnail in order details page

Pdf invoice
- attach pdf invoice 'order placed', 'order paid', 'order processing' and/or 'order completed' emails

Gift cards (fraud prevention kinda)
- Activate gift cards after completing of an order
- Deactivate gift cards after cancelling of an order
- Deactivate gift cards after deleting of an order
- Delete gift card usage history after order cancellation

Return request settings
- Enable return system (can return items previously purchased)
- request number mask (can set ID to like date of request etc)
- number of days return request is avail
- allow file uploads
- select request reasons avail (wrong product, problem with product etc)
- select return request actions (repair, replace, store credit, refund)

# Shipping settings

Common
- estimate shipping enabled on cart page and/or product page
- use city name or zip code for estimate shipping
- 'pick up in store' enabled/disabled
- toggle to ignore additional shipping charge for puis
- display pickup points on the map
- free shipping over X (can set X and include/exclude tax in X)
- Use warehouse location (if several locations to calculate shipping rates)
- consider associated products dimensions and weight (or if only base on main item)
- sort shipping methods by position or shipping cost (position is manually entered when entering the different shipping options like free shipping as 1, standard as 2, express 3 etc)

Notifications
- Notify customer about shipping from multiple locations 
- display shipment events (to customers)
- display shipment events (to store owner (in admin area))

Checkout
- Hide shipping total if shipping is not required
- ship to same address? 
- bypass shipping method page if theres only one

Shipping origin
- first name, last name, email, company, country, state, region, city, address 1/2, zip, phone number, fax number

# TBA settings
TBA
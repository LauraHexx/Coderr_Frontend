# Coderr Frontend

Coderr Frontend is a Vanilla JavaScript project that serves as the user interface for the Coderr platform. It interacts with the Django backend to manage users, offers, orders, and reviews.

## Features

- **User Management**

  - Registration and login for business and customer users
  - Profile view and editing

- **Offers and Orders**

  - Browse and filter offers
  - Create and edit offers (business users)
  - Place and manage orders

- **Reviews**

  - Submit and view reviews for business users
  - Sorting and filtering for reviews

- **File Uploads**

  - Upload profile and offer images

- **Statistics**
  - Display platform statistics (e.g., number of offers, reviews, average rating)

---

## Project Structure

```
frontend/
├── assets/             # Images, icons, fonts
├── scripts/            # Page-specific JS files
├── shared/             # Reusable JS and CSS files
├── styles/             # Page-specific CSS files
├── index.html          # Homepage
├── login.html          # Login page
├── registration.html   # Registration page
├── own_profile.html    # Own profile
├── business_profile.html # Public business profile
├── customer_profile.html # Public customer profile
├── offer_list.html     # Offer overview
├── offer.html          # Offer detail page
├── imprint.html        # Imprint
├── privacy_policy.html # Privacy policy
```

## Requirements

- A running Coderr backend ([see backend README](https://github.com/LauraHexx/Coderr_Backend/))
- Visual Studio Code with Live Server or similar

## Installation & Usage

1. **Start the backend**  
   Make sure the backend is running (see backend README).

2. **Open the frontend**  
   Open the frontend project in Visual Studio Code.

3. **Start Live Server**  
   Right-click on `index.html` → "Open with Live Server" (or open manually in your browser).

---

## Development

- You can directly edit HTML, CSS, and JS files.
- Communication with the backend is done via REST API calls (see `shared/scripts/api.js`).

## Testing

The frontend does not include automated tests. Changes can be tested directly in the browser.

---

this is the readme
# Real Estate Project

## Overview
This is a full-stack real estate web application built using Django for the backend and React for the frontend, with Ailons CSS for styling. The platform allows users to browse, search, and filter real estate listings, providing an intuitive and interactive user experience.

## Technologies Used
### Backend (Django)
- Django REST Framework (DRF) for API development
- PostgreSQL/MySQL for the database
- Django authentication system
- Django CORS Headers for cross-origin requests

### Frontend (React)
- React Router for navigation
- Axios for API requests
- React Hooks (`useState`, `useEffect`) for state management
- Context API for global state management

### Styling (Ailons CSS)
- Predefined components for a clean UI
- Responsive design for mobile and desktop
- Custom styling overrides for a unique look

## Features Implemented
### Backend Features
- **User Authentication:** Login, registration, and JWT-based authentication
- **Property Listings:** CRUD operations for property management
- **Filtering & Sorting:** API endpoints to filter properties based on price, location, and type
- **Search Functionality:** Full-text search for property listings
- **Image Uploads:** Support for uploading property images
- **Favorites System:** Users can save their favorite listings

### Frontend Features
- **User Dashboard:** Displays user profile, saved properties, and recent activity
- **Property Listings Page:** Shows a list of properties with filtering and sorting options
- **Property Details Page:** Displays detailed information, images, and contact options
- **Responsive Design:** Ensures a seamless experience on all devices
- **Animated UI Components:** Enhances the user experience with smooth transitions

## Installation & Setup
### Backend Setup
1. Clone the repository:
   ```sh
   git clone https://github.com/your-username/real-estate-app.git
   cd real-estate-app/backend
   ```
2. Create and activate a virtual environment:
   ```sh
   python -m venv venv
   source venv/bin/activate  # On Windows, use `venv\Scripts\activate`
   ```
3. Install dependencies:
   ```sh
   pip install -r requirements.txt
   ```
4. Run migrations:
   ```sh
   python manage.py migrate
   ```
5. Start the Django server:
   ```sh
   python manage.py runserver
   ```

### Frontend Setup
1. Navigate to the frontend directory:
   ```sh
   cd ../frontend
   ```
2. Install dependencies:
   ```sh
   npm install
   ```
3. Start the React development server:
   ```sh
   npm run dev
   ```

## API Endpoints
| Method | Endpoint | Description |
|--------|----------|-------------|
| GET | `/api/properties/` | Fetch all properties |
| GET | `/api/properties/<id>/` | Fetch a single property |
| POST | `/api/properties/` | Create a new property (Authenticated) |
| PUT | `/api/properties/<id>/` | Update a property (Authenticated) |
| DELETE | `/api/properties/<id>/` | Delete a property (Authenticated) |
| POST | `/api/auth/register/` | Register a new user |
| POST | `/api/auth/login/` | Login a user |
| POST | `/api/properties/favorites/` | Add property to favorites |

## Future Improvements
- **Advanced filtering** (e.g., by amenities, nearby schools, etc.)
- **Integration with Google Maps** for location-based searching
- **Chat system** for direct communication between buyers and sellers
- **Push notifications** for property updates

## Contributing
Feel free to fork the project, make improvements, and submit pull requests.

## License
This project is licensed under the MIT License.

---
Enjoy coding! 🚀


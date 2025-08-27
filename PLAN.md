# PARQUEATE CERCA Mobile App Recreation Plan

## Overview
Recreate the exact mobile parking app interface shown in the image using HTML, CSS, and minimal JavaScript for interactions.

## Design Analysis
- **Theme**: Dark blue background (#1e3a5f or similar) with green accent buttons (#4ade80)
- **Layout**: Mobile-first responsive design
- **Typography**: Clean, modern font (will use Google Fonts)
- **Components**: Multiple screens with forms, dropdowns, and navigation

## Screens to Implement

### 1. Welcome/Landing Screen
- App logo with green location pin and leaf design
- "PARQUEATE CERCA" branding
- Descriptive text about finding nearby parking
- Green "Comienza ya" (Start now) button

### 2. Login Screen ("Inicio de sesión")
- Back arrow navigation
- Email input field
- Password input field with eye icon
- Green "Iniciar sesión" button
- "¿Olvidaste tu contraseña?" link
- "¿No tienes cuenta? Regístrate" link

### 3. Registration Screen ("Regístrate")
- Back arrow navigation
- Camera icon for profile photo
- Multiple form fields:
  - Document type dropdown
  - Document number
  - Names
  - Surnames
  - Vehicle plate
  - Vehicle type dropdown
  - Email
  - Phone number
  - Password with eye icon
- Terms and conditions checkbox
- Green "Registrarse" button

### 4. Password Recovery Screens
- "Recupera tu contraseña" screen with phone/email input
- "Ingrese su código de recuperación" with 6-digit code input
- "Ingrese su nueva contraseña" with password fields

### 5. Dropdown Components
- Document type selector (Cédula de ciudadanía, Tarjeta de identidad, etc.)
- Vehicle type selector (Automóvil, Motocicletas, Bicicletas, etc.)

## Technical Implementation

### File Structure
```
src/
├── app/
│   ├── page.tsx (Welcome screen)
│   ├── login/
│   │   └── page.tsx
│   ├── register/
│   │   └── page.tsx
│   ├── recovery/
│   │   └── page.tsx
│   └── layout.tsx
├── components/
│   ├── MobileScreen.tsx
│   ├── FormInput.tsx
│   ├── CustomSelect.tsx
│   └── BackButton.tsx
└── styles/
    └── mobile-app.css
```

### Key Features
1. **Mobile-responsive design** (max-width: 400px containers)
2. **Custom styled form inputs** matching the design
3. **Dropdown menus** with custom styling
4. **Navigation between screens** using Next.js routing
5. **Interactive elements** (password visibility toggle, form validation)
6. **Exact color scheme** and typography matching the original

### CSS Approach
- Use Tailwind CSS for rapid styling
- Custom CSS for specific mobile app aesthetics
- Flexbox for layout management
- CSS Grid for form layouts
- Custom dropdown styling to match the design

### JavaScript Functionality
- Form validation
- Password visibility toggle
- Dropdown interactions
- Screen navigation
- Mobile-optimized touch interactions

## Implementation Steps
1. Create the main layout and mobile container
2. Implement the welcome/landing screen
3. Build the login screen with form inputs
4. Create the registration screen with all form fields
5. Implement password recovery screens
6. Build custom dropdown components
7. Add navigation between screens
8. Style all components to match the exact design
9. Test responsive behavior and interactions
10. Optimize for mobile viewing

## Success Criteria
- Exact visual match to the provided design
- Fully responsive mobile interface
- Working form interactions and navigation
- Clean, maintainable code structure
- Proper accessibility considerations

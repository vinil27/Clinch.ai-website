# UI Components & Usage Guidelines

## 1. Buttons
### Primary Button
- **Usage**: Main call-to-action (e.g., "Start Building", "Sign Up").
- **Style**: Solid `Deep Espresso` background, White text, Pill shape.
- **States**:
  - *Default*: Opacity 100%.
  - *Hover*: Lift up 2px, shadow increases.
  - *Active*: Scale down 0.98.

### Secondary Button
- **Usage**: Alternative actions (e.g., "Learn More", "Go Back").
- **Style**: Transparent background, 2px `Deep Espresso` border.
- **States**:
  - *Hover*: Background becomes `Soft Clay`.

## 2. Forms
### Text Input
- **Style**: White background, 1px border `#E0E0E0`, rounded corners (12px).
- **Focus State**: Border becomes `Deep Espresso` (2px), slight brown glow.
- **Validation**:
  - *Error*: Border becomes `#C0392B`.
  - *Success*: Border becomes `#27AE60`.

## 3. Navigation
### Main Navbar
- **Layout**: Logo on left, Links centered/right, CTA on far right.
- **Links**: `Inter` font, medium weight.
- **Hover**: Underline animation with `Rust Orange` color.

## 4. Cards
### Content Card
- **Usage**: displaying features, blog posts, or widgets.
- **Style**: White background, large border-radius (24px).
- **Elevation**:
  - *Rest*: Small diffused shadow.
  - *Hover*: Lifts up, shadow becomes more prominent.

## 5. Animation Tokens
Use these CSS classes to apply standard organizational motion.
- `.fade-up`: Smooth entry for sections.
- `.hover-lift`: For interactive cards and buttons.
- `.pulse`: For attention-grabbing badges.

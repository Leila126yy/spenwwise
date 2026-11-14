# SpendWise - Dashboard Shell (CSS Grid & Flexbox)

## What I built
A static SpendWise dashboard shell with sidebar, header, summary and 6 category cards.

## Files
- `index.html` - Structure: sidebar, header, summary, 6 cards (Food, Transport, Rent, Entertainment, Savings, Utilities)
- `style.css` - All layout and theme

## What each part does
- **CSS Grid:** `.layout` (sidebar + main) and `.cards` (3 columns)
- **Flexbox:** header, sidebar nav, summary, and inside each card
- **CSS Variables:** `:root` has --brand, --accent, --surface, --card-bg, --text-primary, --text-secondary
- **Responsive:** @media (max-width:768px) collapses to single-column
- **Micro-interactions:** cards use transform + box-shadow in 200ms on hover and focus
- **Dark theme:** @media (prefers-color-scheme: dark) overrides only :root variables
- **No absolute positioning** used for layout
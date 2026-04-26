# Mobile-Friendliness Improvements — TODO

## Plan Overview
Improve user experience on small devices (phones) for the Libras House website.

---

## Steps

### HTML (`index.html`)
- [ ] 1. Update viewport meta tag to include `viewport-fit=cover`
- [ ] 2. Add `inputmode` attributes to form inputs (tel, email)
- [ ] 3. Add mobile menu backdrop element
- [ ] 4. Update mobile menu JS: smooth transitions, scroll lock, backdrop click close

### CSS (`librashouse-style.css`)
- [ ] 5. Add safe-area inset support for notched devices
- [ ] 6. Fix hero height on mobile (`min-height: auto` with padding)
- [ ] 7. Ensure all tap targets ≥ 44×44px
- [ ] 8. Disable hover effects on touch devices (`@media (hover: hover)`)
- [ ] 9. Add smooth mobile menu transition (transform + opacity)
- [ ] 10. Ensure `background-attachment: scroll` on all mobile breakpoints
- [ ] 11. Optimize form inputs (`font-size: 16px`, remove tap highlight)
- [ ] 12. Improve footer stacking on tiny screens
- [ ] 13. Add `overscroll-behavior: contain` when menu is open
- [ ] 14. WhatsApp float safe-area positioning
- [ ] 15. Use `aspect-ratio` for testimonial images
- [ ] 16. Reduce card padding on very small screens (< 400px)
- [ ] 17. Add `touch-action: manipulation` to buttons/links
- [ ] 18. Enhance `prefers-reduced-motion`


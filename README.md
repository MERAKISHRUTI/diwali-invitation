# Fursat ki Raat

Buildless, responsive invitation. Open dist/index.html, or serve dist using any static server.

## Edit

All event details and all eight role choices live in dist/config.js. Set whatsappNumber to the host's country-code-prefixed number (digits only, e.g. 919876543210). The same configured recipient is used for every guest. Replace the venue address placeholder. The reference date is used as 4 November 2026, 9 pm India time; edit date, end, dateLabel and time together if needed.

The cream playing cards, purple deck, diya, orange typography, countdown, plan, rulebook, name/attendance form, role grid and guest card follow all eight screenshots. Instagram UI, presenter and video captions are excluded. The partially obscured Chief Guest description and games introduction use editable complementary copy; no specific games or schedule were legible beyond the supplied start time.

RSVP validates name, attendance and role. It prepares a URL-encoded WhatsApp message, using same-tab navigation for in-app browser compatibility. Guests still need to press Send in WhatsApp. Until a valid host number is configured it shows a helpful message and never opens a random recipient.

Google Fonts is optional; local serif and sans-serif fallbacks work offline. Animations honor reduced motion and remain visible when JavaScript is disabled. No RSVP data is stored on a server.

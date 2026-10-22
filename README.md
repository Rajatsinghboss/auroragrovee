# Aurora Grove — Luxury Hotel Website

A responsive, single-page website for Aurora Grove, Manali, with a forest-green and champagne visual system, real property photos from a publicly listed accommodation gallery, room enquiry prompts, an external online-booking partner link, and basic on-page SEO.

## Current implementation
- Responsive navigation and mobile layout
- Hotel-specific photo gallery with full-screen image viewer
- Room sections for the Double Room and Four-Bed Mixed Dormitory Room listed publicly
- Date and guest selector with validation
- Online booking hand-off to the existing Lodging World property listing
- Enquiry message builder with optional WhatsApp hand-off
- Google Maps directions and embedded map
- SEO title, description, Open Graph metadata, semantic headings, alt text, reduced-motion support

## Important before launch
1. **Configure direct enquiries.** In `index.html`, set `WHATSAPP_NUMBER` to the hotel's WhatsApp number including country code and digits only, e.g. `919876543210`. Until configured, the enquiry action offers the online booking partner as a fallback.
2. **Connect a live booking engine.** The date form currently validates dates and sends guests to the external booking partner. It does not itself query inventory, confirm reservations, collect payments, or send booking emails. For native live availability and checkout, connect a hotel PMS/booking-engine API and payment provider.
3. **Confirm room details and policies.** Verify room categories, capacity, prices, check-in/check-out, inclusions, accessibility and pet policy with the property before publishing.
4. **Use approved photo assets.** The current gallery uses publicly reachable image URLs from a third-party accommodation listing for Aurora Grove. Replace these with hotel-owned/authorized original images for long-term hosting and confirmed usage rights.
5. **Add contact details.** Add the hotel's approved phone number, email address and official booking URL once supplied.
6. **SEO launch checklist.** Add the final production domain to canonical metadata and sitemap, connect Google Search Console, submit the sitemap, and add structured Hotel/LodgingBusiness data only after verifying the property details.

## Deploy with GitHub Pages
1. Open the repository's **Settings → Pages**.
2. Under **Build and deployment**, select **Deploy from a branch**.
3. Choose branch `main` and folder `/ (root)`, then Save.
4. Wait for the Pages deployment workflow to finish; GitHub will show the published URL in Settings → Pages.

## External booking link
https://www.lodging-world.com/in/hotels/aurora-grove-in-manali-914791886

## Property location used in the page
Manu Temple Road, Old Manali, Manali, Himachal Pradesh 175131, India.

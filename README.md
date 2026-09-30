# SPARK Launch Website

React + Vite launch website for SPARK V4.

## Included

- Real SPARK V4 screenshots supplied by the product owner
- Asymmetric dark/editorial launch page
- SAGE, CLAW, approval gate, local-first memory, voice/contact content
- Pricing page at `/pricing`
- FAQ at `/faq`
- Terms at `/terms`
- Privacy Policy at `/privacy`
- Refund Policy at `/refunds`
- EU/UK digital-content withdrawal page at `/withdrawal`
- Branded 404
- Lenis + GSAP ScrollTrigger motion with reduced-motion support
- Explicit pre-checkout acceptance step

## Before production launch

1. Replace `PADDLE_CHECKOUT_URL` in `src/main.jsx` with the real Paddle checkout destination.
2. Confirm the exact legal seller identity and final business/contact details.
3. Have the legal pages reviewed for the jurisdictions in which you sell.
4. Configure the Paddle product, checkout terms/consent, fulfillment and refund settings.
5. Deploy the production build to Netlify.

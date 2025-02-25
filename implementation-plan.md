# ImprovLens Landing Page Implementation Plan

## Project Overview
ImprovLens is a React Native mobile app for wedding guests to capture and share candid moments at weddings and events. The app features seamless photo sharing with limited shots per guest, creating a unique collection of perspectives from celebrations. Available on iOS and Android with a launch date of June 1, 2025.

## Technical Stack
- **Framework**: Next.js
- **Styling**: Tailwind CSS
- **Animations**: Framer Motion
- **Type Safety**: TypeScript

## Hosting Recommendation: Vercel vs Hostinger

### Vercel
- **Pros**:
  - Created by the team behind Next.js (optimal compatibility)
  - Automatic deployments from GitHub
  - Built-in CI/CD pipeline
  - Preview deployments for PRs
  - Edge functions & image optimization
  - Seamless custom domain setup
  - Free tier available

- **Cons**:
  - Can be more expensive at scale
  - Limited server-side capabilities in free tier

### Hostinger
- **Pros**:
  - Generally lower cost for basic hosting
  - More server configuration control
  - Good customer support
  - Often includes email hosting

- **Cons**:
  - Not specifically optimized for Next.js
  - Manual deployment process
  - No built-in CI/CD
  - Requires more configuration

**Recommendation**: Vercel provides the best developer experience for Next.js projects with seamless deployments, optimizations, and a free tier that's sufficient for a marketing landing page. The tight integration with Next.js makes it the clear choice.

## Page Structure

1. **Header**
   - Logo
   - Navigation (Features, Pricing, About, Contact)
   - CTA button (Download/Waitlist)

2. **Hero Section**
   - Main headline and subheading
   - App value proposition
   - Primary CTA
   - App preview/mockup image
   - Subtle animation effects

3. **Features Section**
   - Key app features with icons/illustrations
   - Brief descriptions
   - Visual mockups

4. **How It Works**
   - Step-by-step explanation
   - Visual process flow

5. **Testimonials/Use Cases**
   - Wedding photography examples
   - Testimonial quotes

6. **Pricing Plans**
   - Free tier
   - Premium options
   - Feature comparison

7. **FAQ Section**
   - Common questions and answers

8. **Download/CTA Section**
   - App store links
   - Final conversion prompt

9. **Footer**
   - Navigation links
   - Social media links
   - Contact information
   - Copyright

## Implementation Phases

### Phase 1: Setup & Header/Hero (Current Focus)
- Project structure setup
- Responsive header component
- Hero section with animation
- Basic styling and responsiveness

### Phase 2: Core Sections
- Features section
- How It Works section
- Mobile-first responsive design

### Phase 3: Conversion & Social Proof
- Pricing section
- Testimonials
- FAQ accordion

### Phase 4: Footer & Polish
- Footer implementation
- Final animations and transitions
- Performance optimization
- SEO implementation

## Design Direction
Based on the provided inspiration image, we'll implement:
- Dark theme with purple/blue gradient accents
- Clean, minimal UI with ample whitespace
- Modern typography with clear hierarchy
- Subtle animations for engagement
- Mobile-first responsive design 
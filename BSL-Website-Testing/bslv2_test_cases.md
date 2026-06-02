🧪 Test Cases: Brain System Limited (BSL) Website

URL: https://techcloudltd.work/demo/bslv2/
Type: Frontend & Responsive Testing
Date: 2026-06-01

1. Page Load & Performance

| TC ID | Test Case          | Steps                         | Expected Result                                                            | Priority |
| ----- | ------------------ | ----------------------------- | -------------------------------------------------------------------------- | -------- |
| PL-01 | Initial page load  | Open URL in browser           | Page loads within 3 seconds                                                | High     |
| PL-02 | Title verification | Check browser tab             | Title shows "Brain System Limited – Democratizing Artificial Intelligence" | High     |
| PL-03 | Meta description   | Inspect `<meta>` tags         | Meta description is present and meaningful                                 | Medium   |
| PL-04 | Favicon presence   | Check browser tab icon        | Favicon is visible                                                         | Low      |
| PL-05 | No console errors  | Open DevTools console on load | Zero JavaScript errors                                                     | High     |
| PL-06 | HTTPS / SSL        | Check address bar             | Secure padlock shown, no warnings                                          | High     |


2. Navigation / Header

| TC ID  | Test Case             | Steps              | Expected Result             | Priority |
| ------ | --------------------- | ------------------ | --------------------------- | -------- |
| NAV-01 | Logo visible          | Load page          | Logo renders correctly      | High     |
| NAV-02 | Logo click            | Click logo         | Redirects to homepage/top   | High     |
| NAV-03 | Nav links present     | Inspect header     | All menu items visible      | High     |
| NAV-04 | Hover state           | Hover links        | Visual hover effect appears | Medium   |
| NAV-05 | Active link highlight | Navigate sections  | Active section highlighted  | Medium   |
| NAV-06 | Sticky header         | Scroll page        | Header stays fixed          | Medium   |
| NAV-07 | Mobile hamburger      | Resize ≤768px      | Hamburger appears           | High     |
| NAV-08 | Menu toggle           | Click hamburger    | Menu opens/closes           | High     |
| NAV-09 | Mobile link click     | Click link in menu | Menu closes + navigates     | High     |

3. Hero / Banner Section

| TC ID   | Test Case          | Steps             | Expected Result                 | Priority |
| ------- | ------------------ | ----------------- | ------------------------------- | -------- |
| HERO-01 | Hero text visible  | View top section  | Headline/subheadline visible    | High     |
| HERO-02 | CTA button present | Check hero        | CTA button visible              | High     |
| HERO-03 | CTA click          | Click CTA         | Navigates correctly             | High     |
| HERO-04 | Hero image         | Observe section   | Image/animation loads correctly | Medium   |
| HERO-05 | Text contrast      | Check readability | WCAG AA compliance              | High     |


4. Content Sections

| TC ID   | Test Case         | Steps         | Expected Result              | Priority |
| ------- | ----------------- | ------------- | ---------------------------- | -------- |
| CONT-01 | Sections load     | Scroll page   | All sections visible         | High     |
| CONT-02 | Images load       | Scroll page   | No broken images             | High     |
| CONT-03 | Icons render      | Observe icons | Icons display correctly      | Medium   |
| CONT-04 | Text readability  | Read content  | No overlap/truncation        | High     |
| CONT-05 | Heading structure | Inspect HTML  | Proper H1 → H2 → H3          | Medium   |
| CONT-06 | Card alignment    | Check layout  | Proper grid alignment        | Medium   |
| CONT-07 | Animations        | Scroll page   | Animations trigger correctly | Low      |


5. Links & Buttons

| TC ID  | Test Case      | Steps                | Expected Result       | Priority |
| ------ | -------------- | -------------------- | --------------------- | -------- |
| LNK-01 | Internal links | Click section links  | Smooth scroll works   | High     |
| LNK-02 | External links | Click external links | Opens new tab         | Medium   |
| LNK-03 | Broken links   | Test all links       | No 404 errors         | High     |
| LNK-04 | Hover state    | Hover buttons        | Visual feedback shown | Medium   |
| LNK-05 | Focus state    | Tab navigation       | Focus outline visible | Medium   |


6. Forms (if present)

| TC ID   | Test Case           | Steps                | Expected Result            | Priority |
| ------- | ------------------- | -------------------- | -------------------------- | -------- |
| FORM-01 | Form visible        | Open contact section | All fields visible         | High     |
| FORM-02 | Placeholder         | Inspect fields       | Helpful placeholders shown | Medium   |
| FORM-03 | Required validation | Submit empty form    | Error messages shown       | High     |
| FORM-04 | Email validation    | Enter invalid email  | Error shown                | High     |
| FORM-05 | Successful submit   | Submit valid form    | Success message shown      | High     |
| FORM-06 | Mobile form         | Test on 375px        | Layout not broken          | High     |


7. Footer

| TC ID  | Test Case      | Steps         | Expected Result           | Priority |
| ------ | -------------- | ------------- | ------------------------- | -------- |
| FTR-01 | Footer visible | Scroll bottom | Footer displays correctly | High     |
| FTR-02 | Copyright      | Check footer  | Correct text present      | Medium   |
| FTR-03 | Footer links   | Click links   | Navigation works          | High     |
| FTR-04 | Social icons   | Check icons   | Links correct             | Medium   |

8. Responsive / Viewport Testing

| TC ID   | Test Case     | Viewport    | Expected Result      | Priority |
| ------- | ------------- | ----------- | -------------------- | -------- |
| RESP-01 | Mobile 320px  | 320×568     | No horizontal scroll | High     |
| RESP-02 | Mobile 375px  | 375×667     | Stack layout         | High     |
| RESP-03 | Mobile 425px  | 425×767     | Single column        | High     |
| RESP-04 | Tablet        | 768×1024    | 2-column layout      | High     |
| RESP-05 | Laptop        | 1024×768    | Desktop layout       | High     |
| RESP-06 | Large screen  | 1440px      | Centered layout      | Medium   |
| RESP-07 | No overflow   | All         | No horizontal scroll | High     |
| RESP-08 | Image scaling | All         | Responsive images    | High     |
| RESP-09 | Font size     | Mobile      | Readable text        | High     |
| RESP-10 | Touch targets | Mobile      | ≥44px buttons        | High     |
| RESP-11 | Grid reflow   | Breakpoints | Proper layout shift  | Medium   |
| RESP-12 | Media scaling | All         | Responsive embeds    | Medium   |
| RESP-13 | Hero mobile   | 375px       | No clipping          | High     |
| RESP-14 | Landscape     | 667×375     | Layout adapts        | Medium   |

9. Cross-Browser Testing

| TC ID | Browser        | Version | Expected Result | Priority |
| ----- | -------------- | ------- | --------------- | -------- |
| CB-01 | Chrome         | Latest  | Full support    | High     |
| CB-02 | Firefox        | Latest  | Full support    | High     |
| CB-03 | Safari         | Latest  | Full support    | High     |
| CB-04 | Edge           | Latest  | Works correctly | Medium   |
| CB-05 | Android Chrome | Latest  | Mobile OK       | High     |
| CB-06 | iOS Safari     | Latest  | Mobile OK       | High     |

10. Accessibility (A11y)

| TC ID   | Test Case        | Method         | Expected Result     | Priority |
| ------- | ---------------- | -------------- | ------------------- | -------- |
| A11Y-01 | Alt text         | Inspect HTML   | All images have alt | High     |
| A11Y-02 | Keyboard nav     | Tab test       | Fully accessible    | High     |
| A11Y-03 | Contrast         | Lighthouse     | WCAG AA passed      | High     |
| A11Y-04 | ARIA labels      | Inspect        | Proper labels       | Medium   |
| A11Y-05 | Screen reader    | NVDA/VoiceOver | Logical reading     | Medium   |
| A11Y-06 | Lighthouse score | Audit          | ≥80 accessibility   | Medium   |

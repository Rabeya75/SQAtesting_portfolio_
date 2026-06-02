1. Page Load & Performance
TC IDTest CaseStepsExpected ResultPriorityPL-01Initial page loadOpen URL in browserPage loads within 3 secondsHighPL-02Title verificationCheck browser tabTitle shows "Brain System Limited – Democratizing Artificial Intelligence"HighPL-03Meta descriptionInspect <meta> tagsMeta description is present and meaningfulMediumPL-04Favicon presenceCheck browser tab iconFavicon is visibleLowPL-05No console errorsOpen DevTools console on loadZero JavaScript errors on initial loadHighPL-06HTTPS / SSLCheck address barSecure padlock shown, no mixed-content warningsHigh

2. Navigation / Header
TC IDTest CaseStepsExpected ResultPriorityNAV-01Logo visibleLoad pageLogo renders correctly with no distortionHighNAV-02Logo clickClick on logoRedirects to homepage / top of pageHighNAV-03All nav links presentInspect headerAll menu items (Home, About, Services, Contact, etc.) visibleHighNAV-04Nav link hover stateHover over each linkVisual hover effect (color/underline) appearsMediumNAV-05Active link highlightNavigate to each sectionActive/current section is highlighted in navMediumNAV-06Sticky headerScroll down the pageHeader stays fixed at top while scrollingMediumNAV-07Hamburger menu (mobile)Resize to ≤768pxHamburger icon appears; desktop nav hidesHighNAV-08Hamburger open/closeClick hamburger on mobileMenu opens; click again or outside to closeHighNAV-09Mobile nav link clickOpen menu, click a linkMenu closes and navigates to correct sectionHigh

3. Hero / Banner Section
TC IDTest CaseStepsExpected ResultPriorityHERO-01Hero text visibleView above-the-fold areaHeadline and subheadline render clearlyHighHERO-02CTA button presentCheck hero sectionCall-to-action button(s) are visibleHighHERO-03CTA button clickClick primary CTANavigates to correct section or pageHighHERO-04Hero image/animationObserve heroBackground image or animation loads without glitchMediumHERO-05Hero text contrastCheck text over backgroundText is readable (WCAG AA: contrast ratio ≥ 4.5:1)High

4. Content Sections
TC IDTest CaseStepsExpected ResultPriorityCONT-01All sections loadScroll through full pageAll sections (About, Services, Features, etc.) are presentHighCONT-02Images loadScroll through pageNo broken image icons (alt text shows if image fails)HighCONT-03Icons renderObserve icon setsAll icons are sharp and correctly sizedMediumCONT-04Text readabilityRead all contentNo truncated or overlapping textHighCONT-05Section heading hierarchyInspect HTMLHeadings follow H1 → H2 → H3 orderMediumCONT-06Cards / grids alignmentObserve feature/service cardsCards are evenly spaced and aligned in gridMediumCONT-07Animations / transitionsScroll down slowlyScroll-triggered animations fire at correct positionsLow

5. Links & Buttons
TC IDTest CaseStepsExpected ResultPriorityLNK-01Internal anchor linksClick each section linkSmooth scroll to correct sectionHighLNK-02External linksClick any external linkOpens in new tab (target="_blank")MediumLNK-03No broken linksClick all links on pageNo 404 or error pagesHighLNK-04Button hover stateHover over all buttonsVisual feedback on hover (color shift, shadow)MediumLNK-05Button focus stateTab through buttonsVisible focus ring for keyboard accessibilityMedium

6. Forms (if present)
TC IDTest CaseStepsExpected ResultPriorityFORM-01Form fields visibleNavigate to Contact/Demo sectionAll form fields render correctlyHighFORM-02Placeholder textInspect fieldsPlaceholder text guides user inputMediumFORM-03Required field validationSubmit empty formError messages shown for required fieldsHighFORM-04Email validationEnter invalid email → submitError: "Please enter a valid email"HighFORM-05Successful submissionFill valid data → submitSuccess message or redirect confirmedHighFORM-06Form on mobileUse form on 375px viewportFields are tappable and keyboard doesn't break layoutHigh

7. Footer
TC IDTest CaseStepsExpected ResultPriorityFTR-01Footer visibleScroll to bottomFooter renders completelyHighFTR-02Copyright textCheck footerCopyright year and company name presentMediumFTR-03Footer linksClick each footer linkAll links navigate correctlyHighFTR-04Social media iconsObserve footerIcons present and link to correct profilesMedium

8. Responsive / Viewport Testing
8.1 Breakpoint Definitions
BreakpointWidthMobile S320pxMobile M375pxMobile L425pxTablet768pxLaptop1024pxLaptop L1440px4K2560px

8.2 Responsive Test Cases
TC IDTest CaseViewportExpected ResultPriorityRESP-01Layout at 320px320×568No horizontal scroll; content fitsHighRESP-02Layout at 375px375×667Text, images, cards stack verticallyHighRESP-03Layout at 425px425×767Single-column layout; no overflowHighRESP-04Layout at 768px768×10242-column grid visible; nav may switch to desktopHighRESP-05Layout at 1024px1024×768Full desktop nav visible; multi-column layoutHighRESP-06Layout at 1440px1440×900Wide layout centered; no excessive whitespaceMediumRESP-07No horizontal scrollAll viewportsoverflow-x never triggers scrollbarHighRESP-08Images scaleResize browserImages scale proportionally, never overflowHighRESP-09Font size readabilityMobile viewportsMin font size 14px; no tiny unreadable textHighRESP-10Touch targets375px (mobile)Buttons/links ≥ 44×44px tap areaHighRESP-11Grid reflow375px → 768px → 1024pxGrid columns change at correct breakpointsMediumRESP-12Video/embed scalingAll viewportsEmbedded media is responsive (16:9 ratio maintained)MediumRESP-13Hero section mobile375pxHero text readable; CTA button not clippedHighRESP-14Landscape orientation667×375 (landscape mobile)Layout adapts; no broken sectionsMedium

9. Cross-Browser Testing
TC IDBrowserVersionExpected ResultPriorityCB-01ChromeLatestFull functionalityHighCB-02FirefoxLatestFull functionalityHighCB-03SafariLatestFull functionalityHighCB-04EdgeLatestFull functionalityMediumCB-05Chrome (Android)LatestMobile layout correctHighCB-06Safari (iOS)LatestMobile layout correctHigh

10. Accessibility (A11y)
TC IDTest CaseTool/MethodExpected ResultPriorityA11Y-01Image alt textInspect <img> tagsAll images have meaningful alt attributesHighA11Y-02Keyboard navigationTab through pageAll interactive elements are reachable via TabHighA11Y-03Color contrastChrome DevTools / LighthouseAll text meets WCAG AA (4.5:1 normal, 3:1 large)HighA11Y-04ARIA labelsInspect interactive elementsButtons/links have descriptive labelsMediumA11Y-05Screen reader testNVDA / VoiceOverContent is read in logical orderMediumA11Y-06Lighthouse scoreRun Lighthouse auditAccessibility score ≥ 80Medium
cd..


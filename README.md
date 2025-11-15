Experiment 3 — Heuristic Evaluation of an Existing Website or App

NAME: SARANYA S.

REG NO: 212223220101

Aim:

To perform heuristic evaluation on existing websites or apps, identify
usability issues, suggest improvements, implement design changes,
and evaluate their impact using A/B testing.

Tools Used:

• Figma (for redesign and prototype testing)
• Google Forms / Maze (for A/B testing)
• GitHub (for code and documentation)

• Nielsen’s 10 Usability Heuristics framework

Apps/Websites Chosen for Analysis

1. Swiggy – Online food ordering and delivery platform
2. Zomato – Online food ordering and restaurant discovery
platform

Part A: Heuristic Evaluation:

1. Visibility of System Status:
<img width="431" height="255" alt="image" src="https://github.com/user-attachments/assets/6536034a-3048-4d11-a4b8-eee13c5914bf" />


Swiggy:Provides real-time order tracking with clear progress indicators.

Zomato: Shows delivery updates but lacks clear visual cues during
payment loading.

Improvement:Add clear progress indicators during checkout (Zomato).

2. Match Between System and Real World
<img width="434" height="335" alt="image" src="https://github.com/user-attachments/assets/eed6f08f-cffe-4103-9d79-7f9719a1ed4a" />

• Swiggy: Uses familiar food-related terms and icons (cart, offer,
delivery time).
• Zomato: Slightly more technical in “Safety Labels” and “Dining
Mode”.

• Improvement: Simplify technical terms into natural, user-friendly
phrases.

3. User Control & Freedom

Swiggy:Undo is limited for coupon removal.
Zomato:Back navigation reloads pages sometimes.
Blinkit:Best user freedom —quick replace, remove, undo.

Improvement:
• Add quick undo actions (remove coupon, remove item, edit quantity).

4. Consistency & Standards

Swiggy:Mostly consistent but menu layouts vary.
Zomato: Some screens use different card styles.
Blinkit:Very consistent design system.

Improvement:
• Standardize restaurant and dish card layout across all apps.

5. Error Prevention

Swiggy:Allows double-tap accidentally increasing quantity.
Zomato:Coupons fail late at checkout.
Blinkit:Prevents cart mixing errors early.

Improvement:
• Implement button freeze for 1 second after Add to Cart.
• Validate coupons instantly before applying.

6. Recognition Rather Than Recall

Swiggy: Shows recent orders.
Zomato: Shows popular dish recommendations.
Blinkit:Auto-suggest past grocery items (very efficient).

Improvement:
• Add preset delivery instructions and visible customization options.

7. Flexibility & Efficiency

Swiggy:Has reorder shortcuts.
Zomato: Strong search but no quick checkout.
Blinkit:Very efficient “minutes delivery” flow.

Improvement:

• Add “Fast Checkout” or “Order Again” shortcuts in Zomato.

8. Aesthetic & Minimalist Design

Swiggy:Clean UI, but too many promo banners.
Zomato:Heavy typography and information overload.
Blinkit:Very minimalistic and clean.

Improvement:
• Reduce ad sections and show more food content first.

9. Error Diagnosis & Recovery

Swiggy: Error messages are generic.
Zomato:Better error messages but address selection issues remain.

Improvement:
• Add clear, human-readable error explanations.

10. Help & Documentation

Swiggy: FAQs are detailed but long.
Zomato:Good chat support.
Blinkit: Simple and short help sections.

Improvement:
• Add mini tutorials for payment, refunds, and tracking issues.

Part B: Design Improvements (Redesign Implementation)

Based on the heuristic issues, the following design changes were made
in Figma:

Redesigned Checkout Screen (Zomato)

• Added progress indicator (Cart →Address →Payment →
Confirmation)

• Cleaner and larger payment buttons

• Real-time coupon validation

Redesigned Restaurant Page (Swiggy)

• Reduced banner ads

• Standardized dish card (Image →Price →Add Button)

• Larger tap targets

Redesigned Home Screen (Both Apps)

• Simplified category icons

• Visible quick filters

• Highlighted “Repeat Order” area

All redesigned screens uploaded to GitHub.

Part C: A/B Testing (Google Forms / Maze)

Two versions were tested:

Version A (Original)

– Existing Swiggy/Zomato UI
–More ads

–Hidden options
– Slower checkout

Version B (Improved / Redesigned)

–Cleaner layout
–Visible coupon validation
–Consistent card layout
– Faster checkout flow

A/B Testing Results Summary

Metric Version A Version B

Task Completion Time Slower Faster

Number of Clicks More Fewer

User Satisfaction Medium High

Metric Version A Version B

Error Rate Higher Lower

Checkout Success 73% 92%

Overall Preference 28% 72%

Insights:

• Users preferred Version B for clarity and speed.
• Visible progress indicators increased trust.
• Minimal design improved navigation efficiency.

Conclusion

Through heuristic evaluation, Swiggy and Zomato’s usability issues
were identified and addressed. Redesigns in Figma significantly
improved clarity, navigation, and efficiency. A/B testing clearly showed
that Version B (improved) was more intuitive, faster to use, and
preferred by users. This experiment demonstrates the importance of

combining heuristic analysis with real user testing to produce
meaningful UI/UX improvements.

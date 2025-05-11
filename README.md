# FAQ Accordion

A lightweight, customizable accordion component for creating FAQ (Frequently Asked Questions) sections on websites.

## Features

- Responsive design that works on all devices
- Smooth animations for expanding/collapsing content
- Customizable styling options
- Accessible with keyboard navigation and ARIA support
- Zero dependencies

## Installation

```bash
npm install faq-accordion
# or
yarn add faq-accordion
```

## Usage

```javascript
import FAQAccordion from 'faq-accordion';

// Initialize with default options
const accordion = new FAQAccordion('#faq-container');

// Or with custom options
const accordion = new FAQAccordion('#faq-container', {
    singleOpen: true,
    defaultOpen: 0,
    animationDuration: 300
});
```

## Example HTML Structure

```html
<div id="faq-container">
    <div class="faq-item">
        <div class="faq-question">What is FAQ Accordion?</div>
        <div class="faq-answer">A lightweight component for creating FAQ sections.</div>
    </div>
    <!-- More FAQ items -->
</div>
```

## Customization

The component can be styled using CSS variables:

```css
:root {
    --faq-background: #ffffff;
    --faq-question-color: #333333;
    --faq-answer-color: #666666;
    --faq-border-color: #eeeeee;
}
```

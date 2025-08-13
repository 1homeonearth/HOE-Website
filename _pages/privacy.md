<!-- _pages/privacy.md -->
---
title: Privacy Guide
permalink: /privacy/
---

**Core Principles**

- No JavaScript, cookies, analytics, pixels, or external fonts.
- Pages render identically on clearnet and Tor.
- Minimal metadata for fast, low-leak browsing.

**Content Security Policy**

This site sets a strict CSP in the `<head>` of every page:

```

default-src 'self'; frame-ancestors 'none'; base-uri 'none';

```

**Access via Tor**

Use the .onion mirror for best privacy:  
{{ site.onion_url }}

**Keyboard & A11y**

All navigation is keyboard-navigable; the navbar is swipeable on mobile (horizontal scroll), and contrast is tuned for dark backgrounds.

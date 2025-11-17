https://petlovers-21e01a.webflow.io/

TC01 – Validate Main Menu Navigation  

Precondition: Website is published

Steps:

1 - Open the website in a browser.

2 - Click the “About” menu.

3 - Click the “Projects” menu.

4 -Click the “Contact” menu.

Expected Result:
Each menu option opens the correct section without errors or delays.

Actual Result:
Failded

TC02 – Validate Mobile Responsiveness

Steps:

1 - Open website in Chrome DevTools.

2 - Select a mobile device (iPhone 12).

3 - Check alignment and layout.

Expected Result:
Layout adapts for mobile with no overlapping elements.

Actual Result:
Failed - Responsiveness is broken on all mobile formats except 470px

TC03 – Validate External Links

Steps:

1 - Click "IEFP" link.

2 - Click "PORTO." link.

3 - Click "Start up Portugal" link

Expected Result:
Links open in new tab and point to the correct URLs.

Actual Result:
Pass – All external links function correctly.

TC04 – Test Contact Form Submission

Steps:

1 - Fill all contact fields.

2 - Click “Send”.

Expected Result:
Form submits successfully or validation triggers when fields are missing.

Actual Result:
Failed

TC05 – Validate Page Performance

Steps:

1 - Open site in incognito.

2 - Measure load time.

Expected Result:
Page loads under 3 seconds.

Actual Result:
Pass – Initial load time ~2 seconds.

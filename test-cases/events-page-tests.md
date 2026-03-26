### Title: Verify opening, closing, and hover states of the burger menu on a narrowed desktop browser

**Preconditions:**
1. User is on the GreenCity Events page (https://www.greencity.cx.ua/#/greenCity/events), using a desktop browser.
2. The desktop browser window width is reduced until the main header navigation collapses and the burger menu icon appears.

**Test Steps:**

| Step | &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;Action&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; | Data | Expected Result |
| :---: | :--- | :---: | :--- |
| 1 | Hover over the burger menu icon. | - | The cursor changes into a pointer. |
| 2 | Click the burger menu icon. | - | Menu pop-up with navigation links opens. The burger menu icon animates and changes into a "cross" (close) icon. |
| 3 | Hover over the "cross" (close) icon. | - | The cursor changes into a pointer. |
| 4 | Click the "cross" (close) icon. | - | Menu pop-up closes. The 'cross' icon animates back into a burger menu icon. |

## [GC-001]: Verify opening, closing, and hover states of the burger menu on a narrowed desktop browser

**Preconditions:**
1. User is on the GreenCity Events page (https://www.greencity.cx.ua/#/greenCity/events), using a desktop browser.
2. The desktop browser window width is reduced until the main header navigation collapses and the burger menu icon appears.

**Test Steps:**

| Step | Action | Data | Expected Result |
| :---: | :--- | :---: | :--- |
| 1 | Hover over the burger menu icon. | - | The cursor changes into a pointer. |
| 2 | Click the burger menu icon. | - | Menu pop-up with navigation links opens. <br>The burger menu icon animates and changes <br>into a 'cross' (close) icon. |
| 3 | Hover over the 'cross' (close) icon. | - | The cursor changes into a pointer. |
| 4 | Click the 'cross' (close) icon. | - | Menu pop-up closes. <br>The 'cross' icon animates back into <br>a burger menu icon. |

## [GC-002]: Verify that an unauthorized user cannot react (like) a comment

**Preconditions:**
1. User is not logged in (unauthorized).
2. User is on an Event Details page that contains at least one comment.

**Test Steps:**

| Step | Action | Data | Expected Result |
| :---: | :--- | :---: | :--- |
| 1 | Hover over the 'Like' button on any comment. | - | The cursor changes into a pointer. |
| 2 | Click the 'Like' button. | - | A 'Log In' / 'Sign In' pop-up window appears. <br>The reaction count on the comment does not increase. |

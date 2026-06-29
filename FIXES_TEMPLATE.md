# Fixes Summary

Name:Navinkumar BM
Registration number:731623201038
Time spent:6-7 Hours

## Bugs fixed

For each item, include the broken behavior, files changed, and how you verified the fix.

1. Issue:Student Search is not efficient like different letter case and extra spaces.
   Files changed:App.jsx
   Explanation:Updated the search logic to trim spaces and perform case-insensitive matching.
   Verification:Tested using uppercase, lowercase, and inputs with extra spaces.

2. Issue:Theme persistence after page refresh.
   Files changed:App.jsx / useLocalStorage.js
   Explanation:Stored the selected theme in localStorage.
   Verification:Changed the theme, refreshed the page, and conformed the selected theme.

3. Issue:Sidebar navigation was not switching between Dashboard, Assignments, etc...
   Files changed:Sidebar.jsx and App.jsx
   Explanation:Updated the navigation state handling so that clicking each menu item correctly displays the selected section.
   Verification:Tested all sidebar menu options and confirmed that Dashboard, Assignments, and Announcements opened correctly without errors.

## UI improvements made 

Only list improvements that directly support the assignment requirements.

-Improved assignment list rendering.
-Improved responsive layout.
-Fixed sidebar navigation behavior.

## Out-of-scope changes

List any intentional refactors or behavior changes that were not directly required. Write `None` if you did not make any.

-None

## Testing performed

- Desktop:Tested on Windows laptop
- Tablet:Tested using browser responsive view
- Mobile:Tested using Chrome mobile view
- Browser console checked:No console errors
- Refresh/persistence checked:Theme persisted after refresh

## Known limitations

-None

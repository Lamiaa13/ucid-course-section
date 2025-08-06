# Dev Log: 5
## Date / Module: 2025-03-10 / Module 5
## Name: Lamia Rahman

### GitHub Issue Links Assigned
- [x] User Profile Page Development #48  
https://github.com/MoodFlix/moodflix-repo/issues/48
  - Acceptance Criteria: Editable profile with viewing history
  - Started Date: 2025-03-05
  - Target Completion Date: 2025-03-08
  - Finished Date: 2025-03-07
  - Summary: Created profile UI with React hooks and context API

- [x] Watchlist Functionality #51  
https://github.com/MoodFlix/moodflix-repo/issues/51
  - Acceptance Criteria: Add/remove movies with local persistence
  - Started Date: 2025-03-06
  - Target Completion Date: 2025-03-10
  - Finished Date: 2025-03-09
  - Summary: Implemented watchlist with Redux and localStorage

- [ ] Responsive Navigation Redesign #54  
https://github.com/MoodFlix/moodflix-repo/issues/54
  - Acceptance Criteria: Mobile-first navigation with accessibility
  - Started Date: 2025-03-08
  - Target Completion Date: 2025-03-12
  - Finished Date: N/A
  - Summary: Completed mobile navigation prototype

### Noteworthy Learnings and resource links
- React Context API patterns: [React Docs](https://react.dev/learn/scaling-up-with-reducer-and-context)
- Redux Toolkit for state management: [Redux Toolkit Guide](https://redux-toolkit.js.org/introduction/getting-started)
- localStorage best practices: [MDN Web Docs](https://developer.mozilla.org/en-US/docs/Web/API/Window/localStorage)
- Progressive Web App techniques: [PWA Fundamentals](https://web.dev/progressive-web-apps/)
- Accessible navigation patterns: [WAI-ARIA Authoring Practices](https://www.w3.org/WAI/ARIA/apg/patterns/navigation/)
- CSS clip-path for animations: [CSS-Tricks Guide](https://css-tricks.com/clipping-masking-css/)

### Problems/Difficulties Encountered
- State synchronization between Context API and Redux
- localStorage size limitations for large watchlists
- Offline functionality implementation challenges
- Mobile navigation performance on low-end devices
- Focus management in complex navigation menus
- Persistent state hydration on page refresh

### Positive Shoutout to Team Member(s)
- Isaiah Auguste (isauguste): Solved complex Redux middleware issue
- Gerard Almenares (GerardA8): Integrated watchlist with backend API
- Ashutosh Chalise (ash-neon): Optimized mobile navigation performance
- Rylie Schroers (rks32): Conducted thorough accessibility testing
- James Mullins (JamezM546): Implemented PWA service worker

### What can be improved individually?
- Better separation of concerns in state management
- More comprehensive error boundaries
- Improved offline experience design
- Earlier performance testing on target devices
- Better documentation of component props

### What can be improved as a team?
- Standardize state management approach
- Create shared utility hooks library
- Implement end-to-end testing with Cypress
- Establish performance budget for key interactions
- Schedule regular code quality reviews
- Create UX research sessions with real users

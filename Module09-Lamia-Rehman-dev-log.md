# Dev Log: Indivisual
## Date / Module: 2025-04-15 / Module 9
## Name: LAmia REhman

### GitHub Issue Links Assigned
- [x] Implement User Profile API #89  
https://github.com/MoodFlix/moodflix-repo/issues/89
  - Acceptance Criteria: RESTful endpoints for CRUD operations on user profiles
  - Started Date: 2025-04-10
  - Target Completion Date: 2025-04-15
  - Finished Date: 2025-04-14
  - Summary: Developed GET/PUT endpoints with JWT authentication
  
- [ ] Profile Picture Upload Integration #92  
https://github.com/MoodFlix/moodflix-repo/issues/92
  - Acceptance Criteria: Cloud storage integration with size validation
  - Started Date: 2025-04-13
  - Target Completion Date: 2025-04-18
  - Finished Date: N/A
  - Summary: Completed AWS S3 bucket configuration

### Noteworthy Learnings and resource links
- JWT refresh token implementation: [Auth0 Docs](https://auth0.com/docs/secure/tokens/refresh-tokens)
- AWS S3 presigned URLs for secure uploads
- Optimistic UI updates in React: [React Query Guide](https://tanstack.com/query/latest)
- Postman testing automation with collections

### Problems/Difficulties Encountered
- CORS configuration issues between frontend and backend
- State synchronization after profile updates
- AWS IAM permission errors during S3 setup
- Timezone conversion in user activity logs

### Positive Shoutout to Team Member(s)
- GerardA8: Helped debug CORS configuration for 3 hours
- Lamiaa13: Designed excellent profile UI components
- JamezM546: Provided AWS credential best practices

### What can be improved individually?
- Better documentation of API endpoints during development
- More thorough test coverage for edge cases
- Earlier communication about blocking issues

### What can be improved as a team?
- Standardize API response formats
- Create shared Postman collection
- Schedule brief daily standups during crunch periods

# Project Progress Group 43

## Group number
Group 43

## Contributors
- Gowtham Basker - 2214024
- Amru Ahmed Riham - 2250965
- Shihab Marey - 2380836
- Sajid Rahman - 2226381
- Mohammad Shayan Mahmoudi - 2374415
- Reginald Ibe - 2216626
- Ashaz Khan - 2322275
- Nguyen Xuan Tien (Gabriel) - 2332255

## Sprint 3 - Review and Retrospective

### Sprint Review
**Summary of Completed Work:**  
During Sprint 3, we established the foundational architecture for our funding platform. We successfully created login and registration components, implemented basic admin verification workflows, and developed project creation screens with document upload capabilities. The platform includes a virtual wallet system with transaction verification and the beginning of an investment workflow. We've also set up the UI framework with Material UI components and implemented responsive design principles with a dark theme. The platform now demonstrates a cohesive user experience with secure authentication and role-based access control.

**Reflection on Challenges:**  
The integration of document verification features has presented more complexity than initially anticipated. While we have document upload functionality, we haven't yet implemented the admin-initiated document request system. The investment feature workflow also requires enhancement, particularly in milestone tracking and fund release mechanisms. Additionally, we've identified a need for better user engagement features such as the proposed news section. These challenges highlight the need for more detailed planning of complex workflows before implementation begins.

**Next Steps:**  
Our immediate focus will be on implementing the document request system for admins, enhancing the investment workflow with syndicate management capabilities, and adding the news feed integration to improve user engagement with SDG-related content. We will also refine existing components with standardized error handling and loading indicators to improve the overall user experience and platform reliability.

### Sprint Goal and Demoed Features
**Sprint Goal:** Built core platform infrastructure and investment workflows

| Demoed Feature | Feedback |
|----------------|----------|
| User Authentication | Functional login/registration system with secure password handling |
| Project Creation | Multi-step form works but needs document category organization |
| Investment Process | Basic investment workflow implemented; needs milestone tracking enhancement |
| Admin Panel | Transaction verification panel operational; needs document request feature |
| Virtual Wallet | Deposit and transaction tracking implemented; verification system needs refinement |

### Completed Tasks

| Epic-User Story ID | Epic Description | Acceptance criteria | Assigned To | Done? |
|-------------------|------------------|---------------------|-------------|-------|
| User Registration - 001 | Create Account - I can access and personalize my interactions | Users can register, login, and access role-specific dashboards | Shayan | Yes |
| Project Creation - 002 | Submit project proposals - I can showcase my ideas to investors | Innovators can create projects with supporting documents | All | Yes |
| Investment Interface - 003 | Invest in promising projects - I can support innovation initiatives | Investors can view and invest in projects | Tien | Partial |
| Admin Verification - 007 | Verify platform activity - Ensure platform integrity | Admins can verify transactions and users | Gowtham | Partial |
| UI Framework - 008 | Access intuitive interface - I can easily navigate regardless of device | Platform has responsive design with dark theme | Shihab | Yes |

### New/Revised Tasks
**Epic - User Registration (001)**

| Task ID | Description |
|---------|-------------|
| 001-4 ID | Implement functionality for users to upload an identity document for verification |
| 001-5 Admin | Develop an admin panel where admins can log in, review user identity documents, and approve or reject them |
| 001-6 | Implement two-factor authentication for enhanced account security |

**Epic - Document Request System (010)**

| Task ID | Description |
|---------|-------------|
| 010-1 | Create DocumentRequestDialog component for admins to request specific documents |
| 010-2 | Develop DocumentRequestsList component for user dashboard |
| 010-3 | Implement backend API endpoints for document requests |
| 010-4 | Add notification system for document request alerts |
| 010-5 | Create document upload interface for responding to requests with deadlines |

**Epic - News Integration (011)**

| Task ID | Description |
|---------|-------------|
| 011-1 | Create NewsService with API integrations for SDG and investment content |
| 011-2 | Develop NewsPage component with filtering and categorization |
| 011-3 | Add dashboard news widget for displaying relevant article previews |
| 011-4 | Implement article detail view and bookmarking functionality |
| 011-5 | Add user preference system for news personalization |

### Sprint Retrospective

| What went well | What could have gone better | What will we do differently? (Enhancements) |
|----------------|----------------------------|-------------------------------------------|
| The authentication system with JWT implementation provides secure user access with appropriate role-based permissions. | The document management system lacks organization by category and request functionality. | We will implement a comprehensive document request system with status tracking and notifications. |
| The project creation interface guides innovators through a structured process with document uploads. | The investment workflow doesn't fully implement milestone-based fund release. | We'll enhance the investment tracking with clearer milestone verification steps and escrow management. |
| The admin verification panel for transactions provides good oversight capabilities. | Meeting scheduling challenges have slowed some integration work. | We'll establish fixed meeting slots after lectures/labs and set clearer agendas for online meetings. |
| The Material UI implementation creates a consistent and professional user experience. | Some components lack comprehensive error handling and loading states. | We'll implement standardized error handling patterns and loading indicators across all components. |
| The virtual wallet functionality supports the core investment processes. | News and engagement features are missing, reducing platform stickiness. | We'll add the news integration to provide relevant SDG and investment content to users. |

## Sprint 4 Plan

### Sprint Goal
Enhance the platform with document request functionality for admins, syndicate management features for investors, and integrate a news section to increase user engagement with SDG-related content. These enhancements will improve platform security, user collaboration, and content relevance.

### Sprint Leads
Reggie will lead the funding rounds and syndicate management implementation. Gowtham will oversee the document request and verification system development. Both leads will coordinate closely to ensure their components integrate seamlessly for a consistent user experience.

### Sprint Backlog
**Epic: User Registration (001)**

| Task ID | Description | Story Point | Assigned To |
|---------|-------------|-------------|-------------|
| 001-1 | Database: Design database schema for user data storage | 5 | Shayan |
| 001-2 | Backend: Develop backend API for user registration | 5 | Shayan |
| 001-3 | Frontend: Create front-end registration form with validations | 8 | Shayan |
| 001-4 | Implement functionality for users to upload an identity document for verification | 5 | Shayan |
| 001-5 | Develop an admin panel where admins can log in, review user identity documents, and approve or reject them | 8 | Shayan |
| 001-6 | Implement two-factor authentication for enhanced account security | 5 | Shayan |

**Epic: Project Pitching (002)**

| Task ID | Description | Story Point | Assigned To |
|---------|-------------|-------------|-------------|
| 002-1 | Database: Create database model for storing project pitches | 5 | Riham |
| 002-2 | Backend: Implement backend API for pitch submission | 5 | Riham |
| 002-3 | Frontend: Develop front-end pitch submission interface | 8 | Riham |
| 002-4 | Frontend: Add input validation for pitch submission form | 3 | Riham |
| 002-5 | Backend: Test API and UI integration for pitch submission | 3 | Riham |

**Epic: Investor Preferences (003)**

| Task ID | Description | Story Point | Assigned To |
|---------|-------------|-------------|-------------|
| 003-1 | Backend: Build backend logic to save investor preferences | 5 | Tien |
| 003-2 | Frontend: Design and implement front-end for preference setup | 8 | Tien |
| 003-3 | Backend: Implement matching logic to filter projects | 5 | Tien |
| 003-4 | Backend: Test the preference filtering functionality | 3 | Tien |

**Epic: Funding Rounds & Syndicate Management (004)**

| Task ID | Description | Story Point | Assigned To |
|---------|-------------|-------------|-------------|
| 004-1 | Database: Create database schema to store funding round data | 5 | Reggie |
| 004-2 | Backend: Develop backend API for managing funding rounds | 8 | Reggie |
| 004-3 | Frontend: Enhance investment interface with milestone tracking | 8 | Reggie |
| 004-4 | Backend: Implement escrow fund management for milestone releases | 5 | Reggie |
| 004-5 | Frontend: Create syndicate creation and management interface | 8 | Reggie |
| 004-6 | Backend: Develop syndicate voting mechanisms for investment decisions | 5 | Reggie |
| 004-7 | Frontend: Implement dashboard visualizations for investment tracking | 5 | Reggie |

**Epic: Growth Tracking (005)**

| Task ID | Description | Story Point | Assigned To |
|---------|-------------|-------------|-------------|
| 005-1 | Database: Build database model to track project growth metrics | 5 | Sajid |
| 005-2 | Backend: Develop backend logic for calculating growth metrics | 8 | Sajid |
| 005-3 | Frontend: Create front-end dashboard to visualize growth tracking | 8 | Sajid |
| 005-4 | Backend: Test integration of growth metrics with user interface | 3 | Sajid |

**Epic: Messaging Platform (006)**

| Task ID | Description | Story Point | Assigned To |
|---------|-------------|-------------|-------------|
| 006-1 | Database: Design database schema for storing messages | 5 | Ashaz |
| 006-2 | Backend: Implement backend API for sending/receiving messages | 8 | Ashaz |
| 006-3 | Frontend: Develop front-end messaging interface | 8 | Ashaz |
| 006-4 | Backend: Integrate real-time notifications for new messages | 5 | Ashaz |
| 006-5 | Backend: Write test cases for messaging functionality | 3 | Ashaz |

**Epic: Security and Verification (007)**

| Task ID | Description | Story Point | Assigned To |
|---------|-------------|-------------|-------------|
| 007-1 | Backend: Implement user verification process | 5 | Gowtham |
| 007-2 | Backend: Add password encryption and storage security | 5 | Gowtham |
| 007-3 | Backend: Integrate a two-factor authentication system | 8 | Gowtham |
| 007-4 | Backend: Perform security testing for data breaches and vulnerabilities | 5 | Gowtham |

**Epic: UI and Accessibility (008)**

| Task ID | Description | Story Point | Assigned To |
|---------|-------------|-------------|-------------|
| 008-1 | Frontend: Design wireframes for key platform features | 5 | Shihab |
| 008-2 | Frontend: Implement responsive UI components | 8 | Shihab |
| 008-3 | Frontend: Add accessibility features for visually impaired users | 5 | Shihab |
| 008-4 | Frontend: Test UI performance across devices and browsers | 3 | Shihab |

**Epic: Performance and Reliability (009)**

| Task ID | Description | Story Point | Assigned To |
|---------|-------------|-------------|-------------|
| 009-1 | Backend: Optimize backend performance for high traffic | 5 | All |
| 009-2 | Backend: Conduct load testing to ensure reliability under stress | 8 | All |
| 009-3 | Backend: Set up server-side monitoring tools to detect issues | 5 | All |
| 009-4 | Backend: Write test cases for performance and scalability | 3 | All |

**Epic: Document Request System (010)**

| Task ID | Description | Story Point | Assigned To |
|---------|-------------|-------------|-------------|
| 010-1 | Create DocumentRequestDialog component for admins to request specific documents | 5 |
| 010-2 | Develop DocumentRequestsList component for user dashboard | 5 |
| 010-3 | Implement backend API endpoints for document requests | 8 |
| 010-4 | Add notification system for document request alerts | 5 |
| 010-5 | Create document upload interface for responding to requests with deadlines | 5 |

**Epic: News Integration (011)**

| Task ID | Description | Story Point | Assigned To |
|---------|-------------|-------------|-------------|
| 011-1 | Create NewsService with API integrations for SDG and investment content | 8 |
| 011-2 | Develop NewsPage component with filtering and categorization | 5 |
| 011-3 | Add dashboard news widget for displaying relevant article previews | 5 |
| 011-4 | Implement article detail view and bookmarking functionality | 5 |
| 011-5 | Add user preference system for news personalization | 3 |

**Detailed Focus on Funding Rounds Implementation:**  
As the lead for the Funding Rounds epic, I (Reggie) have completed the initial investment workflow that allows investors to contribute funds to projects. The current implementation includes:
1. Project browsing and filtering functionality with intuitive categorization
2. Investment dialog with amount specification and validation against minimum thresholds
3. Basic transaction verification through admin panel with risk assessment indicators
4. Fund tracking in the virtual wallet with transaction history

My current focus is on enhancing these features with:
1. Syndicate formation to allow investors to pool resources and collaborate on larger investments
2. Milestone-based escrow release mechanisms that align funding with project progress
3. Voting systems for collective investment decisions with appropriate weighting
4. Advanced investment analytics and performance tracking with visual representations
5. Improved visualizations for funding progress that enhance transparency

The main challenges encountered involve designing a flexible escrow system that can accommodate various milestone structures while maintaining transparency and security for both investors and innovators. Our approach involves creating a state transition system that tracks each milestone's progress and requires appropriate verification before releasing funds.

This implementation directly supports SDG 9 by creating more accessible and transparent funding mechanisms for infrastructure and innovation projects, particularly in developing regions. The syndicate feature will enable smaller investors to participate in larger projects, democratizing the funding landscape and increasing the pool of available capital for sustainable development initiatives.

## Appendix - Updated Project Backlog

| Epic | US ID | As a.. | I want to.. | So that... | F/NF/UI | Priority | Status |
|------|-------|--------|------------|------------|---------|----------|--------|
| User Registration | 001 | User | Create Account | I can access and personalize my interactions | F | High | Partial |
| Project Creation | 002 | Innovator | Submit project proposals | I can showcase my ideas to investors | F | High | Completed |
| Investment Interface | 003 | Investor | Invest in projects | I can support innovation initiatives | F | High | Partial (60%) |
| Funding & Syndicates | 004 | Investor | Form investment groups | I can participate in larger funding opportunities | F | Medium | In Progress (30%) |
| Milestone Tracking | 005 | User | Track project progress | I can monitor investment performance | F | Medium | Not Started |
| Messaging Platform | 006 | User | Communicate with stakeholders | I can discuss details and build relationships | F | High | Not Started |
| Admin Verification | 007 | Admin | Verify users and transactions | I can ensure platform integrity | F | High | Partial (50%) |
| UI and Accessibility | 008 | All users | Access intuitive and inclusive interface | I can easily navigate regardless of device | F | High | Completed |
| Performance and Reliability | 009 | User | Experience stable and responsive platform | I do not face interruptions while using platform | NF | High | Not Started |
| Document Requests | 010 | Admin | Request verification documents | I can thoroughly verify user identity | F | High | Not Started |
| News Integration | 011 | User | Access relevant SDG news | I can stay informed about trends and opportunities | F | Medium | Not Started |

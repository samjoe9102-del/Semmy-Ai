
# Semi AI — UI/UX Specification

## 1. Design Vision

Semi AI should feel like a professional, intelligent, trustworthy executive assistant — not a traditional chatbot.

The interface should be:
- Clean
- Modern
- Professional
- Simple to navigate
- Proactive without being distracting
- Optimized for mobile first
- Responsive for larger screens

Primary brand colors:
- Gold — intelligence, value, premium quality
- Blue — trust, reliability, technology

The interface should consistently reinforce Semi AI's identity as a research and productivity assistant.

---

## 2. Welcome Screen

### Purpose
Introduce Semi AI before account creation.

### Elements
- Semi AI logo
- Short tagline
- Gold and blue visual identity
- Get Started button
- Privacy/security note
- Version information

### Behavior
Tapping "Get Started" opens the three-slide introduction.

---

## 3. Introduction — Three Slides

### Slide 1 — Meet Semi AI

Message:
"Meet your AI Executive Assistant."

Purpose:
Introduce Semi AI as an intelligent assistant designed to help users get important work done.

Visual direction:
- Abstract AI assistant illustration
- Gold and blue color palette
- Modern technology elements
- No humanoid robot imagery

---

### Slide 2 — Get Work Done

Message:
"Research. Organize. Get things done."

Purpose:
Show how Semi AI helps users manage:
- Tasks
- Emails
- Schedules
- Research
- Documents

Visual direction:
- Organized task cards
- Email/inbox elements
- Calendar elements
- Research/document visuals
- Gold and blue accents

---

### Slide 3 — Private. Secure. Trusted.

Message:
"Your information stays under your control."

Purpose:
Communicate Semi AI's commitment to:
- Privacy
- Security
- Encryption
- User-controlled memory
- Verified information

Visual direction:
- Shield/security illustration
- Encrypted data elements
- Secure connection imagery
- Gold and blue branding

### Navigation
- Progress indicator
- Next button
- Skip option
- Final button: "Let's Get to Work"

After the third slide, users proceed to account creation.

---

## 4. Sign-Up Screen

### Fields
- Full Name
- Email
- Phone Number
- Password
- Confirm Password

### Actions
- Create Account
- Continue with Google
- Continue with Microsoft

### Validation
- Valid email format required
- Strong password required
- Password confirmation must match
- Required fields cannot be empty
- Inline error messages

### Trust Message

"Your data is encrypted and protected."

Links:
- Terms of Service
- Privacy Policy

---

## 5. Email Verification

### Purpose
Verify the user's email address.

### Elements
- Verification message
- Verification code or link
- Resend verification option
- Change email option

### Success
After successful verification, continue to preferences.

### Error States
Clearly explain:
- Invalid code
- Expired code
- Verification failure
- Email delivery problems

---

## 6. User Preferences

Users can configure:
- Name
- Time zone
- Work hours
- Notification preferences
- Memory preferences

Semi AI should use these preferences to provide more relevant assistance.

---

## 7. Integration Setup

### Initial Integrations
- Google Workspace
- Microsoft 365
- Trello
- ClickUp

### Future Integrations
- LinkedIn
- Upwork
- Instagram
- Additional supported productivity and communication services

Each integration should display:
- Service name
- Connect button
- Permissions requested
- Connected/disconnected status
- Disconnect option

Users must understand what information Semi AI can access before granting permission.

---

## 8. Home Dashboard

The home screen is the primary workspace.

### Layout

Top area:
- Personalized greeting
- Notification indicator

Main area:
- Email Summary card
- Immediate Tasks card

Primary action:
- Large request input area
- Text input
- Voice input

### Example Greeting

"Good morning."

### Request Area

Placeholder:
"How can I help you today?"

Users can:
- Type a request
- Speak a request

---

## 9. Home Dashboard Interactions

### Email Summary Card
Tapping opens recent emails.

### Tasks Card
Tapping opens today's prioritized tasks.

### Request Area
Submitting a request:
1. Analyze the request.
2. Select the appropriate Semi AI mode.
3. Research or access relevant information.
4. Process the request.
5. Return the result.
6. Display completion status.

### Notifications
The notification icon opens:
- Important tasks
- Upcoming events
- Important emails
- Completed task notifications
- Corrections and system notices

---

## 10. Research Results

Semi AI should present research results as:

### Summary First
A concise answer should appear first.

### Expand
Users can expand the result to see:
- Detailed explanation
- Supporting information
- Sources
- Relevant documents
- Additional context

Semi AI should clearly distinguish verified information from uncertainty.

---

## 11. Task Manager

### Main Views
- All
- In Progress
- Completed

### Task Information
Each task displays:
- Task title
- Description
- Priority
- Due date
- Status

### Actions
- Create
- View
- Edit
- Complete
- Delete

Deletion requires confirmation.

### Sorting
Users can sort by:
- Priority
- Deadline

### Priority
Semi AI ranks tasks using:
- Urgency
- Importance
- Deadline
- User preferences
- Learned routines, where permitted

---

## 12. Task Details

Task details include:
- Title
- Description
- Priority
- Deadline
- Status
- Related email
- Related calendar event

### Version 1 Limitation

Subtasks are intentionally excluded from Version 1 and reserved for a future update.

---

## 13. Email Manager

### Inbox
Display:
- Sender
- Subject
- Time/date
- Priority
- Read/unread status

### Priority Levels
- High
- Medium
- Low

### Priority Detection

Semi AI can identify priority using signals such as:
- User-defined VIP contacts
- Urgent language
- Mentioned deadlines
- Important requests

Priority detection should improve over time with user feedback.

### Actions
- Read
- Draft reply
- Follow up
- Archive
- Delete

Sending or deleting requires confirmation unless the user has explicitly enabled an appropriate automation.

---

## 14. Email Drafting

When Semi AI drafts an email:

1. Generate the draft.
2. Display a preview.
3. Allow editing.
4. Allow tone selection where appropriate.
5. Require confirmation before sending.

The user remains in control of outgoing communication.

---

## 15. Calendar and Appointments

### Views
- Daily
- Weekly

### Actions
- Create appointment
- Edit appointment
- Delete appointment
- Reschedule appointment

Desktop layouts may support drag-and-drop rescheduling.

### Reminders
Users can configure reminder timing.

For missed important reminders:
1. Send a follow-up reminder.
2. Allow snooze.
3. Send another reminder according to the configured schedule.
4. Stop after the configured reminder limit.

Semi AI should avoid excessive notifications.

---

## 16. Memory

Semi AI may remember user-approved information such as:
- Name
- Recurring tasks
- Preferences
- Relevant email context
- Past discussions
- Projects
- Work routines
- Upcoming events

Users must be able to control what Semi AI remembers.

Memory should be transparent and manageable through Settings.

---

## 17. Notifications

Notification style should be formal and clear.

Notifications may cover:
- Important tasks
- Upcoming events
- Important emails
- Unread emails
- Completed tasks
- Corrections
- System/security events

Important reminders may continue until:
- Completed
- Viewed
- Snoozed
- Dismissed

---

## 18. Sequential Task Processing

When multiple tasks are requested, Semi AI processes them separately and sequentially.

Example:

1. Research information.
2. Complete the first task.
3. Notify the user.
4. Move to the next task.
5. Notify the user when complete.

This reduces confusion and provides clear progress visibility.

---

## 19. Self-Correction

When Semi AI identifies an error:

1. Correct the information.
2. Notify the user.
3. Explain what was corrected.
4. Provide the updated information.

The correction should be visible rather than silently changing important information.

---

## 20. Offline Mode

Basic functionality should remain available without an internet connection.

Users may:
- View saved tasks
- Create tasks
- Update tasks
- View saved summaries
- Draft email responses

When connectivity returns:
- Changes synchronize
- Conflicts are handled clearly
- Users are notified when synchronization completes

The interface should clearly indicate offline status.

---

## 21. Settings

Settings should contain:

### Account
- Personal information
- Password/security
- Account verification

### Integrations
- Connected services
- Permissions
- Disconnect controls

### Notifications
- Reminder preferences
- Notification preferences

### Memory
- View stored memories
- Delete individual memories
- Disable memory

### Privacy
- Data export
- Permanent data deletion
- Privacy controls

---

## 22. Voice Interaction

Voice input must be available from Version 1.

Users should be able to:
- Start voice input
- Stop recording
- Review transcription
- Submit the request

Voice and text should lead to the same request-processing system.

---

## 23. Custom Workflows

Future workflow interface should allow users to create rules such as:

"When I receive an email from Client A:
1. Summarize the email.
2. Create a follow-up task.
3. Set a reminder for 24 hours."

Sensitive actions must respect user permissions.

---

## 24. Responsive Design

Semi AI should be designed mobile-first.

The interface must adapt to:
- Android phones
- iOS devices
- Tablets
- Desktop/web screens

Controls should remain easy to operate on small screens.

---

## 25. Accessibility

The application should support:
- Readable typography
- Sufficient contrast
- Clear labels
- Screen-reader-friendly controls
- Large touch targets
- Voice interaction

---

## 26. Design Language

Semi AI should maintain a consistent visual language:

- Gold and blue brand accents
- Clean layouts
- Rounded cards where appropriate
- Clear hierarchy
- Minimal visual clutter
- Professional typography
- Subtle animations
- Fast feedback

Animations should guide users rather than distract them.

---

## 27. Core UX Principle

Every screen should answer three questions:

1. What can I do here?
2. What is Semi AI doing?
3. What happens next?

The user should never be left wondering whether an action was successful.

---

## 28. Product Experience Principle

Semi AI should feel like a capable assistant that:

**Researches. Verifies. Organizes. Acts. Reports back.**

The ultimate goal is to help users get important work done reliably and efficiently.

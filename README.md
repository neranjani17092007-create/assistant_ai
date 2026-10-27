# Student Executive Assistant 0.2.0

A portable assistant plugin for academics, projects, hackathons and internships.

## Use
Open the installed Student Executive Assistant in a supported ChatGPT or Codex client. Use the same account and connect Gmail, Google Calendar, Google Drive, Google Contacts and Study Companion as available.

Try:
- Plan my day from my calendar, assignments and important email.
- Show deadlines and conflicts for the next seven days.
- Help me prepare my hackathon submission.
- Draft a reply to this internship email.
- Plan my week with time for classes, projects and rest.
- Compile these notes into a detailed study guide.
- Give me a handoff for my phone.

## Portability
This ZIP contains the plugin manifest, skill, reference and app references. It contains no credentials or copied inbox data. Import/install it through a host that supports this plugin format. Import support and individual connectors vary by client. The same account must authorize its own connections; a ZIP does not transfer them.

The existing private Study Companion dashboard is:
https://neranjani-study-companion.neranjani17092007.chatgpt.site

## Automation
Recurring checks are configured separately in the host and are not installed by extracting this ZIP. The saved schedule and actual connection availability determine background behavior. Local scheduled checks require the host to be available to run. Phone push delivery and operation while the laptop is off have not been verified.

The existing assignment-sync workflow is preserved. A separate planning check may report meaningful new email actions and schedule conflicts, without changing records or sending messages.

## Boundaries
Calendar proposals and reply drafts are suggestions until explicitly saved or sent. Uncertain deadlines stay marked unverified. Existing submissions, notes, research and sharing are preserved.


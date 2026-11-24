# Privacy Policy for LinkedIn Saved Posts Organizer

**Last Updated:** November 23, 2026

## Overview

LinkedIn Saved Posts Organizer ("the Extension") is committed to protecting your privacy. This privacy policy explains how we handle your data.

## Data Collection and Storage

### What the Extension Stores on Your Device

The developer does not collect any data. The Extension stores the following **in your Chrome profile, on your device**. Another Chrome profile on the same computer, and any other computer, does not see it:

- **Post Labels**: Custom labels you create and assign to LinkedIn posts
- **Post Notes**: Personal notes you add to saved posts
- **Label Groups**: The names of groups you make and which of your labels each one holds
- **Post Pins**: Information about which posts you've pinned
- **Post Identifiers**: Unique identifiers for LinkedIn posts you've organized
- **Saved-post index**: For saved posts that appear on your screen, the author's name, their headline, a short text snippet, the post link, and the date the Extension first saw the post (from version 2.7.0 on; posts seen before that have no date). This powers the Ctrl/Cmd+K search, which also looks at your notes, labels and groups.
- **Recent searches**: The last few words you searched for in the panel
- **Revisit list**: the age you picked for the Revisit list, and which posts you dismissed or snoozed there (the post identifier, and for a snooze the date it ends). It is not part of backups. Clear all data removes the dismissals and snoozes.
- **Settings**: Whether the Extension is on or off; your chosen look (skin and theme); the panel's position, size, minimized state and text size; the order of its sections; whether the full label list is open; which label groups are folded; whether you have seen the welcome guide and the latest "What's new"; whether the update badge is showing; and the date you last backed up

### How We Store Your Data

- All data is stored **locally** in your browser using Chrome's Local Storage API
- Your labels, pins and notes are drawn into the LinkedIn saved posts page you have open, under each post. While that page is open they are part of it, like anything else on the page
- **No data is transmitted** to any external servers
- **No data is shared** with third parties
- **No analytics or tracking** is performed by this Extension

### Data You Control

You have complete control over your data:
- You can save a copy of your data at any time with "Back up your data" in the settings menu, and load it back with "Restore from backup"
- You can save a spreadsheet (a CSV file) of the posts the Extension has seen, with your labels, groups, pins, notes and first-seen dates, with "Export as CSV" in the settings menu. The file is made on your computer and saved by your browser. Nothing is sent anywhere. If you share the file or open it in an online service, that service gets what is in it, including your notes and the names of the people who wrote the posts. The file cannot be restored; use "Back up your data" for that.
- "Email this to myself" in the Revisit list opens a new message in the mail program your browser or computer uses for email links. The message holds a subject, the post's author, the start of the post as the Extension stored it, the post link and the first-seen date. The Extension does not fill in a recipient, does not add your notes or labels, and sends nothing. Check the message before you send it; you can change or delete anything in it. A desktop mail app keeps the message on your computer until you send it, though some apps save drafts to your mail account. If your email links open a web mail service, such as Gmail or Outlook on the web, that service receives the message text as soon as the new message opens and may keep it as a draft, even if you never send it. "Copy text" puts the same text on your clipboard instead. A post with no first-seen date (seen before version 2.7.0, or restored from a backup) gives a message with the author and the link only, without the start of the post. The Revisit list itself still shows the stored start of such a post.
- You can delete all labels, groups, pins, notes and Revisit dismissals with "Clear all data" in the settings menu
- You can delete the Extension at any time, which will remove all stored data

## Permissions

### Storage Permission

The Extension requests the `storage` permission to:
- Save your labels, notes, pins, the saved-post index and your settings locally on your device
- Retrieve your saved organizational data when you visit LinkedIn

### Active Tab Permission

The Extension requests the `activeTab` permission so the on/off switch in its toolbar popup can tell the LinkedIn tab you have open to turn the Extension on or off. The popup also reads the address of the tab you have open, on any site, to pick a hint line such as where the organizer will appear. That address is compared in memory and is never stored or sent.

### Host Permission

The Extension requests access to `https://www.linkedin.com/*` to:
- Add organizational features to your LinkedIn saved posts page
- Display your labels, notes, and pins alongside your saved posts

The Extension's script loads on LinkedIn pages and only turns on when you are on your saved posts page.

## Third-Party Services

- The Extension does **not** use any third-party services to process your data
- The Extension does **not** send data to any external servers
- The Extension does **not** include any analytics or tracking
- "Report a bug", "Send feedback" and "Suggest a feature" in the settings menu, "Report a bug" in a warning banner, and "Send feedback" in the toolbar popup open a Google Form in a new tab. The link carries nothing you typed or saved. Anything you type into that form is sent to Google Forms and the developer by you, under Google's privacy policy.
- "Copy diagnostics" puts a short list of counts, such as how many posts the Extension found on the page, together with the Extension version and the page language code, on your clipboard when you press it; it holds no post text, names or links, and nothing is sent anywhere automatically.

## LinkedIn Integration

- This Extension is not affiliated with, endorsed by, or sponsored by LinkedIn Corporation
- The Extension adds its panel, labels, notes and pins to the LinkedIn saved posts page in your browser
- When you first install the Extension, it opens your LinkedIn saved posts page (https://www.linkedin.com/my-items/saved-posts/) once in a new tab. Updates never do this.
- When you press "Load next page", the Extension clicks LinkedIn's own "Show more results" button once, in the tab you have open. It never clicks on its own.
- The Extension does not access or modify your LinkedIn account data directly
- All organizational features are client-side only

## Data Security

- The Extension sends nothing anywhere. Data leaves your device only when you act: a backup or CSV you share, text you copy, or an email draft you open
- All data is stored in Chrome's secure local storage
- The Extension's code makes no network requests of its own. Links you click, such as the feedback form, a LinkedIn post or an email link, open like any other link.

## Children's Privacy

This Extension does not knowingly collect any data from children under 13 years of age.

## Changes to This Policy

We may update this privacy policy from time to time. Any changes will be reflected in the "Last Updated" date at the top of this policy.

## Contact

If you have questions about this privacy policy, please create an issue at https://github.com/jayydees/linkedin-organizer-privacy/issues or use "Report a bug" in the Extension's settings menu.

## Your Rights

You have the right to:
- Access all your data (via "Back up your data")
- Delete all your data (via "Clear all data", or by uninstalling the Extension)
- Request information about data handling practices

## Consent

By installing and using the LinkedIn Saved Posts Organizer Extension, you consent to this privacy policy.

---

**Summary:** This Extension stores all your data in your Chrome profile on your device. We do not collect, transmit, or share any of your data with anyone.

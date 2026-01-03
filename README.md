# ghostroom
An ephemeral anonymous messaging experiment built for high-stakes social interactions and creator feedback.  GHOSTROOM creates temporary "frequencies" (chat rooms) that vanish after 24 hours. Built for bio-links and global vibes, it features a unique Ghost Mode where messages remain blurred until revealed-triggering a 5-second self-destruct "burn."



👻 GHOSTROOM | THE VOID
GHOSTROOM is an ephemeral, anonymous messaging experiment built for creators and communities. It facilitates high-stakes social interactions through temporary "frequencies" that vanish after 24 hours.
⚡ Core Mechanics
 * Vanishing Frequencies: Every room has a hard 24-hour expiration (expiresAt). Once the timer hits zero, the connection is lost forever.
 * Ghost Whispers: Messages sent in Ghost Mode stay blurred. Once a recipient clicks to reveal, they have 5 seconds to read before the message "burns" and becomes unreadable.
 * Identity Masks: Dynamic identity switching. Toggle between:
   * ANON: Pure anonymity.
   * ID: A semi-traceable UID string.
   * CUSTOM: A user-defined mask.
 * Creator Inboxes: Dedicated "Request" rooms for bio-links, featuring real-time unread badges and notification tracking.
🛠 Tech Stack
 * Frontend: HTML5, Tailwind CSS, Lucide Icons.
 * Backend: Firebase (Firestore & Anonymous Authentication).
 * Real-time: Live data syncing via Firestore Snapshots.

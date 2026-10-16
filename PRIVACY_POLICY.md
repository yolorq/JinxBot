# Privacy Policy

**Last updated: October 16, 2026**

This Privacy Policy explains how **Jinx** (the “Bot”) processes
information when it is used on Discord. Jinx is an internal Discord bot
for staff workflow management, including staff statistics, shift
statistics, punishment statistics, spreadsheet synchronization,
compensation calculations, and voice-channel attendance checks.

By adding or using the Bot, you acknowledge this Privacy Policy. If you
do not agree with it, please do not use the Bot.

## 1. Information the Bot Processes

Depending on the command being used, Jinx may process the following
information:

### Discord identifiers and account information

- Discord user IDs, usernames, display names, usernames/tags, and
  nicknames;
- Discord server (guild) IDs, channel IDs, and role IDs;
- membership information needed to check whether a user has an
  authorized role or administrator permission.

### Slash-command information

- the name of the slash command used by a user;
- slash-command options, such as the optional reporting week selected
  for `/areload`;
- interaction IDs and timestamps needed to respond to commands.

The Bot does not read ordinary Discord message content. It does not
intentionally archive a searchable message history or sell message
content.

### Voice-channel information

When the `/avs` command is used, the Bot may process the command user's
current voice channel, the voice channel ID and name, and the Discord
IDs of human members currently in that channel. This is used to compare
attendance with members who have a designated staff role.

The Bot does not intentionally process Discord presence or activity
information.

### Statistics and operational information

The Bot may process staff-related information received from its backend
API or spreadsheets, including:

- punishment statistics, such as warnings, mutes, bans, and reprimands;
- shift and time statistics, including day and night totals;
- spreadsheet values used to calculate staff compensation;
- command execution results, timestamps, error information, and limited
  technical logs.

The Bot does not request Discord passwords, authentication credentials,
or user access tokens.

## 2. How Information Is Used

Information is used only as necessary to:

- recognize and respond to slash commands;
- enforce command access controls based on roles and permissions;
- calculate and display staff, punishment, shift, attendance, and
  compensation statistics;
- synchronize punishment and shift statistics with the operator's
  Google Sheets documents;
- send scheduled operational messages to an authorized Discord user;
- troubleshoot errors, maintain security, prevent abuse, and keep the
  Bot functioning;
- comply with applicable legal obligations.

Jinx does not sell Discord API data, use it for advertising, or use it
to train artificial-intelligence or machine-learning models.

## 3. Storage, Services, and Retention

Depending on the workflow, information may be transmitted to or stored
by the following services:

- **The Bot's backend API**, configured through the deployment
  environment, for staff punishment and shift statistics;
- **Google Sheets and Google APIs**, for staff statistics,
  synchronization data, and compensation-related spreadsheet data;
- **The Bot's hosting and logging infrastructure**, for operating the
  Bot and diagnosing errors.

The Bot's current code does not implement a universal automatic
deletion schedule. Data may remain in the backend API, Google Sheets,
or operational logs until it is no longer needed and is deleted by the
operator or by the relevant service provider. The operator should
remove or anonymize information when it is no longer required for the
Bot's operation, security, or legal obligations.

The operator should identify the actual hosting provider and any
additional service providers before publishing this policy. Those
providers may process information in the countries where they operate.

## 4. Sharing and Disclosure

Jinx does not sell personal information or share Discord API data with
advertisers or data brokers.

Information may be shared with the services listed in Section 3 only
when necessary to operate the Bot and provide its features. The
operator may also disclose information when required by law, to
respond to valid legal process, or to protect the Bot, its users, or
others from fraud, abuse, or security incidents.

## 5. Your Choices and Privacy Requests

Use of the Bot is optional. A user may stop using the Bot, and a server
administrator may remove it from a server. A user may also avoid
invoking commands that require the Bot to process their information.

To request access to, correction of, or deletion of information stored
by the Bot, contact:

**Email: yolorq@proton.me**

Please include enough information to identify the relevant data, such
as the Discord user ID or server ID. Do not send passwords, tokens, or
other login credentials.

The operator will review privacy requests and delete information that
is no longer needed, subject to applicable law, legitimate security
requirements, and information that must be retained by a third-party
service or for a legal obligation.

## 6. Data Security

The operator uses reasonable technical and organizational measures to
protect information processed by the Bot. These measures include
restricting access to Bot credentials and service credentials and
limiting access to the spreadsheets and backend services used by the
Bot. No method of transmission or storage is completely secure.

## 7. Children's Privacy

Jinx is not directed to children. Users must meet the minimum age
requirements applicable to Discord in their jurisdiction. The operator
does not knowingly seek to collect personal information from children
in violation of applicable law.

## 8. Changes to This Policy

This Privacy Policy may be updated when the Bot's features, data
practices, service providers, or legal requirements change. The latest
version will be published at the same public location, and the
“Last updated” date will be revised.

## 9. Contact

For questions or privacy requests, contact:

- **Bot:** Jinx
- **Developer/operator:** yolorq
- **Email:** yolorq@proton.me

This policy describes the Bot's current intended data practices and is
not legal advice.

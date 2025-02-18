This page contains the different release details for Champion Management Platform,

## Version history
| Version | Release Date |
|----|----|
| 2.7 | Dec 02, 2024 |
| 2.6 | May 20, 2024 |
| 2.5 | Dec 21, 2023 |
| 2.4 | Dec 6, 2022 |
| 2.3 | Jul 28, 2022 |
| 2.2 | May 17, 2022 |
| 2.1 | Apr 4, 2022 |
| 2.0 | Dec 9, 2021 |
| 1.3 | Sep 03, 2021 |
| 1.2 | Jul 22, 2021 |
| 1.1 | Apr 1, 2021 |

## Release notes

### 2.7 (Dec 02, 2024)

Below improvements released,

- New Feature: Admins will now be added with "Role" as "Admin" instead of "Manager" in the "MemberList" SharePoint list for consistency in the backend and the UI. Old members added with "Manager" will still continue to work
- Bug Fix: Fixed a bug where Digital Badge shows up blank when there are more than 12 badges in Teams client
- Fixed accessibility issues


### 2.6 (May 20, 2024)

Below improvements released,

- New Feature: Ability for Admins to add/modify other Admins to the app from "Add Member" module.
- Upgraded Teams JS to version 2.21.0
- Updated "Record Event" feature. Events recorded with count greater than '1' will be entered as separate records in the sharepoint list. This is to fix the discrepancy in the report.
- Fixed accessbility issues


### 2.5 (Dec 21, 2023)

Below improvements released,

- New Feature: Ability for Admins to modify App Title from "Manage Config Settings" page under "Admin Settings". The app title is applied to the app header and navigation.
- New Feature: Champions Report for Admins
- New Feature: Leaderboard UI improvements
- New Feature: Champions' names in the app are replaced with Person cards.
- New Feature: Accessibility compliant UI
- Bug Fix: When a tournament name has a apostrophe an error shows up "My Dashboard" of "Tournament of Teams module"
- Removed dependency on 'Sites.Manage.All' API permission. This permission is no longer required to set up the app.
- Upgraded SPFX version from 1.15 to 1.17.

### 2.4 (Dec 6, 2022)

Below improvements released,

- Upgraded SPFx version from 1.13.0 to 1.15.0 and its related NPM packages.
- Upgraded node.js to v16.18.0 which is compatible for SPFx v1.15.0.
- New Feature: Added a new "Admin Tasks" feature, that allows admin to manage champion requests, event requests and config settings.
- New Feature: Ability for the admin to enable events approval and allow them to review the events submitted by champions and approve it.
- New Feature: Ability to send notification to Managers for the pending event requests.
- New Feature: Ability to customize the display name and choices of Region, Group and Country columns in Member List and show/hide these columns in various screens of the application (eg: Add Member , Become a Champion, etc..)
- New Feature: Implemented a functionality to unlock digital badges for Champions based on their points.
- Bug Fix: Digital Badge error for profiles with no profile picture in CDN enabled tenant.
- Bug Fix: Reversal of First name and Last name in Member List for the tenants with display name format as 'LastName FirstName'.
- Other Changes: Few minor UI enhancements

### 2.3 (Jul 28, 2022)

Below improvements released,

- New Feature: Ability to create multiple tournaments using excel template.
- New Feature: Ability to start multiple tournaments at the same time.
- New Feature: Local language support (translations) available for 12 languages.
- Ability to approve/reject multiple requests at a time in manage approval screen.
- New card layout for both Member and Non Member Leaderboards along with improved Search and option to connect with the champions.
- Mobile responsive UI implemented.
- Bug Fix: Incorrect ranking in leaderboard when applying search filters.
- Bug Fix: Inaccurate behavior when adding multiple events of same type in "Record Event" section of Leaderboard.

### 2.2 (May 17, 2022)

Below improvements released,

- Upgraded SPFx version from 1.9.1 to 1.13.0 and its related NPM packages. 
- New Feature: Implemented new logo for the app.
- New Feature: Tournaments Report is available for admins to view visual metrics of completed tournaments along with list of participants for each tournament.
- Other Changes: Few minor UI enhancements, accessibility improvements.

### 2.1 (Apr 4, 2022)

Below improvements released,

- Bug Fix: Addressed an issue with tournament ranks/points not getting updated correctly for some customers within the Tournament of Teams leaderboard.
- New Feature: Multi-Tournament support within the Tournament of Teams module. Organizations can now have multiple tournaments occurring at one time
- New Feature: Introduced image preview feature for the Digital Badge module. Users can now preview their profile pictures with different badges available to them before applying it.
- New Feature: Implemented the Digital Badge feature native to Tournament of Teams. Users can now use the Digital Badge feature without being added as a member of the Champion Management Platform.
- New Feature: Implemented an ability that allows admins to update the logo of the Champion Management Platform that sits in the top application bar. Admins will now see a new icon "Manage App Logo" under the "Admin" section in the home page of the App. Upon replacing the image in the SharePoint library, the new app logo will be shown.
- New Feature: Implemented multilingual support for the application. English support at the moment
- Other Changes: Minor UI fixes.

### 2.0 (Dec 9, 2021)

Below improvements released,

- New and revamped User Interface.
- Upgraded NPM packages to recommended version for better performance, security, and latest fixes
- New module “Tournament of Teams” integrated to “Champion Management Platform” app. 
- “Multiple Badges” feature implemented under “Digital Badges” section. Users can now select from the available badges to apply on profile pictures. Admins will have the ability to manage digital badges and tag them to tournaments created with “Tournament of Teams”
- Connected experiences to app info, support via GitHub issues list, and Feedback portal through application banner
- Enhanced event recording with improved leader board dashboard views and multiple event and recording workflows


### 1.3 (Sep 03, 2021)

Below improvements released,

- Improved App installation process to fix issues while installing the app,
- Upgraded NPM packages to recommended version for better performance, security and latest fixes,
- Fixed an issue where the App is not working as expected when more than 100 champions are added to the system,
- Fixed an issue with incorrect rank of current user being displayed on the side bar under Leaderboard screen

### 1.2 (Jul 22, 2021)

Below improvements released,

- 'Member List' is now created right under 'ChampionManagementPlatform' site. This was created in the root site in version 1.1
- 'Manage Approvals' functionality is added to the App. The Admins can now see this additional feature in the home page. This screen can be used by the admins to Approve/Reject the champion nominations easily.

![Quick Start Guide](../Images/ManageApprovalsIcon.png) 

- Column type for 'Description' is modified to 'Single line of text' from 'Choice'
- 'Member Name' and 'Event Name' columns are added to 'Event Track List' SharePoint list.
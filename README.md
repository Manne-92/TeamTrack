<p align="center">
  <img src="assets/teamtrack-cover.svg" alt="TeamTrack project showcase illustration" width="100%" />
</p>

# TeamTrack

**A learning workspace for courses, teams and live lessons.**

[Svenska](README.sv.md) · [Developer profile](https://github.com/Manne-92)

TeamTrack brings everyday study collaboration into one workspace: course information, team tasks, conversations, shared files and live lessons. Students can move around the website while keeping a call available in the workspace.

**Created by Mahmoud Halbia · Fullstack .NET student project**

This repository is a **public portfolio showcase**. The application implementation is maintained separately in a private repository. It contains no application source code, database dumps, user uploads or service credentials.

## The experience

| Area | What it offers |
| --- | --- |
| Courses | A place for course information, membership and lesson material |
| Teams | Group membership, invitations and a board for study tasks |
| Conversations | Course and team chats, files, replies, reactions and mentions |
| Live lessons | Teacher-led meetings, screen sharing and participant controls |
| Exercise rooms | Small-group work with timers and a return to the main lesson |
| Workspace | Navigation alongside an ongoing call and controls to reopen it |
| Profiles | Profile pictures, initials as a fallback and visual role distinctions |
| Language | Swedish and English interfaces |

## Designed for a study day

1. **Find your course.** Open the course and its lesson information.
2. **Work with your team.** Review tasks, exchange messages and share material.
3. **Join the lesson.** Use voice, camera or screen sharing according to meeting permissions.
4. **Keep working.** Navigate the workspace while the call remains available.
5. **Return to the material.** Revisit the lesson information and attached resources.

Teachers have a different set of meeting controls from students and invited guests. A global account role, course responsibility and participation in a particular meeting are separate concepts in the implementation.

## Engineering overview

| Layer | Technology |
| --- | --- |
| Application | C# and ASP.NET Core MVC on .NET 10 |
| Accounts | ASP.NET Core Identity |
| Data | Entity Framework Core and SQLite |
| Interface | Razor views, CSS and JavaScript |
| Real-time media | LiveKit |
| Media proxy | YARP |
| Automated checks | xUnit and application integration tests |

The project demonstrates server-side access checks, relational data modelling, file metadata and storage separation, reusable presentation components and coordination between a workspace and media controls.

## Current development status

TeamTrack is a working student project under development, rather than a certified production service. Automated tests cover selected access rules and application flows. Real multi-device media, email delivery and production infrastructure require their own environment-specific verification.

**Lesson recording is prepared, but not operational yet.** The teacher-facing choices and service interface are implemented. The real Egress recording adapter, storage and finalisation pipeline still need to be connected before any recording can be created or saved automatically.

## Privacy and source visibility

The public showcase contains selected product and technical information. The full database model, implementation and configuration are kept outside this repository. Credentials and real user data do not belong in a repository, including a private one.

Keeping the server implementation private does not make delivered browser assets invisible. HTML, CSS and JavaScript used by a deployed website can be inspected by its visitors.

## Review or demonstration

A teacher or reviewer can request a guided demonstration or discuss access to the private source with the author. No public demo credentials or production URL are published here.

[Mahmoud Halbia on GitHub](https://github.com/Manne-92)

## Project ownership

This showcase is not an open-source release of the application. Third-party components used by the application retain their respective licenses. The cover image is an illustration for the portfolio, not a screenshot of the live product.

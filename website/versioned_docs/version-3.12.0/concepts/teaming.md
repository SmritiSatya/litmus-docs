---
id: teaming
title: Collaborate with teams
sidebar_label: Teaming
---

---

The ChaosCenter has a built in teaming feature to facilitate collaboration between users using project level role access, the core concepts of which are discussed below.

## Project level roles

Each user has a default project created on user creation by the admin for which they maintain a project level `Owner` access. Every `Owner` has the ability to invite other users into their project with different permission levels, namely `Executor`, and `Viewer`.

Teaming is based on the following principles and each user can have one of the 3 project roles:

- **Owner:** One who created the project and owns it. Only the owner has permission to manage(invite or remove) the members in his/her project. The owner can create resources such as infrastructures, probes, hubs, experiments, etc, schedule chaos experiments, update and delete chaos experiments.They have both create and execute perimissions.
- **Executor:** Members invited with the executor role only have execute and view permissions which allow them to run/stop experiments, use probes etc, they don't have any create/delete permissions.
- **Viewer:** Members having a viewer role can only view the analytics related to the chaos experiments and the chaos experiments themselves, but are not given permission to schedule chaos experiments in the project.

## Role privileges

> Note: A user will be the owner of his/her project by default.

**_As the Project Owner you can:_**

- Invite other users for the following roles:
  - Viewer
  - Executor
- View the list of team members with other details including their role in the project, email-id, date-time of joining the project team.
- Rename your project.
- Remove a member from your project.
- Check the status of the invitation you sent to other members.
- Edit the user role in case the invitation is pending.
- Cancel the invitation.

**_As a Viewer or Executor you can:_**

- Check and Accept/Decline the received invitations.
- Switch and browse any project you are a member of.
- Can leave the project you are a part of, except your own.

> Note: The settings page will not be visible to you if you are browsing someone else’s project. You can only view it if you are the project owner.

## Learn more

- [Invite a team member](../user-guides/invite-team-member.md)
- [Edit/Cancel an invite](../user-guides/edit-invite.md)
- [Accept an invite](../user-guides/accept-invite.md)
- [Remove a team member](../user-guides/remove-team-member.md)

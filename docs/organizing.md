# Organizing Agentic Research @ LSST DESC

This repository is a home for agentic research activities across DESC: discussing ideas, sharing workflows, organizing Office Hours, and developing initiatives around different tools and scientific questions. Participation in any one initiative is optional.

Office Hours are a community activity, initially coordinated by a small set of organizers. Additional co-organizers and co-leads are welcome as the activity matures. A possible future Agentic AI Task Force is an aspiration, not an established organizational unit; its scope and leadership would require appropriate DESC discussion and approval.

## First activity: Lightcone Research Pilot

The [Lightcone Research Pilot](lightcone-pilot/README.md) is the first activity hosted here. It brings DESC scientists together to test and improve Lightcone Research's agentic tooling on LSST science workflows. The **Lightcone Research team**, made up of DESC members, supports the activity with focused engineering, compute, and model inference.

To make effective use of limited resources and keep the effort focused with fast turnaround, the team aims to extend dedicated support to a limited number of projects. Scientific collaborators and the team work together to define a useful test of the tooling and validate the results. Everyone remains welcome to experiment, collaborate, and share work independently of the Lightcone pilot. This activity does not supersede working-group governance or DESC project procedures.

The Lightcone pilot call for ideas is planned for **12 October 2026**, with proposals due by **16 October 2026**. Participating projects will be proposed as sprints at **DESC Sprint Week**, which will serve as the Lightcone pilot kickoff with DESC members. The call remains unpublished pending approval.

## Organizing contacts

| Role | Contact |
| --- | --- |
| Lightcone pilot contact | TBD |
| Office-hours host | TBD |
| DESC working-group contact | TBD |

## Launch configuration and handoff

The repository is intentionally **public**, as confirmed by the organizer. Repository-level Discussions is enabled. Keep administrative access limited to organizers; public participation does not require blanket Write access. Do not designate this as the source repository for organization-wide Discussions.

The five categories below are configured, their names and slugs have been verified, and Polls has been removed. The repository docs now link directly to the category pages.

| Category | Slug | Intended format |
| --- | --- | --- |
| [Lightcone Research Pilot Proposals](https://github.com/LSSTDESC/agentic-research/discussions/categories/lightcone-research-pilot-proposals) | `lightcone-research-pilot-proposals` | Open-ended discussion |
| [Office Hours & Questions](https://github.com/LSSTDESC/agentic-research/discussions/categories/office-hours-questions) | `office-hours-questions` | Question and answer (verified) |
| [Show and tell](https://github.com/LSSTDESC/agentic-research/discussions/categories/show-and-tell) | `show-and-tell` | Open-ended discussion |
| [Announcements](https://github.com/LSSTDESC/agentic-research/discussions/categories/announcements) | `announcements` | Announcement |
| [General](https://github.com/LSSTDESC/agentic-research/discussions/categories/general) | `general` | Open-ended discussion |

The API confirms Q&A status but does not distinguish the announcement format from open-ended discussion. In the GitHub category editor, confirm Announcements still uses **Announcement**, and the other three categories use **Open-ended discussion**.

The [lightcone-research-pilot-proposals.yml](../.github/DISCUSSION_TEMPLATE/lightcone-research-pilot-proposals.yml) and [office-hours-questions.yml](../.github/DISCUSSION_TEMPLATE/office-hours-questions.yml) filenames match the live category slugs. GitHub loads these forms from the default branch (`main`). The `proposal` label exists. Keep the Lightcone call pending until separately approved.

Remaining steps:

1. **Preview both forms.** Open a new discussion in each category to check the fields and required-field validation without posting a test. Confirm that the Lightcone pilot form applies `proposal`.
2. **Check member participation.** Ask a DESC member without repository Write access to verify that they can start a discussion and comment. The current admin account cannot establish this. If creation is blocked, an organization owner should inspect **Organization Settings → Member privileges → Repository discussions → Allow users with read access to create discussions**. The setup did not change organization settings or team permissions.
3. **Confirm roles and scope.** Fill in the contacts above and confirm Lightcone pilot eligibility, available support and access arrangements, and Sprint Week logistics. The call date (October 12), proposal deadline (October 16), and Sprint Week kickoff are established; specify a deadline time and time zone if an exact cutoff is needed. Confirm whether the existing MIT license fits the intended repository content and ownership; it was already present and has been preserved. Each project's outputs need their own appropriate licensing and release approvals.
4. **Approve announcements separately.** Once the repository is ready, approve, post, and pin the **Start Here** welcome discussion in Announcements. Publish and pin **Lightcone Research Pilot — Call for Ideas** only after explicit maintainer approval of the text, scope, resources, access, and timing. Neither announcement has been posted during setup. Do not post placeholder deadlines. Confirm Office Hours details before announcing sessions.

For the GitHub UI steps, see [managing categories](https://docs.github.com/en/discussions/managing-discussions-for-your-community/managing-categories-for-discussions), [discussion forms](https://docs.github.com/en/discussions/managing-discussions-for-your-community/creating-discussion-category-forms), and [read-access discussion permissions](https://docs.github.com/en/organizations/managing-organization-settings/managing-discussion-creation-for-repositories-in-your-organization).

## Ongoing organization

Keep Office Hours details current, welcome other activities, and invite additional organizers as needed. For the Lightcone activity, use its [participation guide](lightcone-pilot/participation.md) for proposal labels and explanations of available support, and add only real participating projects to [Lightcone Research Pilot Projects](lightcone-pilot/projects.md). Follow [DESC policies](https://lsstdesc.org/pages/policies.html) for public sharing, project review, external collaborators, publication, and conduct.

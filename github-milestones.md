# Milestones

GitHub's [Issue tracker](./issues.md) allows you to mark Issues as belonging to particular Milestones - important moments in time of a project.

- Click the `Milestones` button in the project's `Issues` tab to manage milestones.
- Click `New milestone` to create a new one

![Creating a GitHub Milestone that will be used to track progress towards a Sprint](./images/github_new_milestone_form.png)

## Sprint management

Milestones are useful in Agile development, where work is earmarked for particular Sprints.

- individual [Issues](./issues.md) can be added to particular Milestones

The Milestones view shows progress towards each Milestone, including:

- percent completion
- number of open issues
- number of closed issues

**The problem with GitHub's Milestones**: GitHub's project management tools include "[Milestones](https://docs.github.com/en/issues/using-labels-and-milestones-to-track-work/about-milestones)", which are tags that can be associated with any Issue. For example, you could use this to create a "`Sprint 1`" Milestone and mark User Stories that you intend to work on during Sprint 1 with this milestone. In GitHub, only one Milestone can be associated with any Issue. But we will often start work on a User Story during one Sprint but continue working on it in the next. So, we would need to mark that User Story as being related to multiple Sprints. **GitHub's Milestones feature doesn't work for us**.

**The solution**: Instead, use GitHub's Labels feature to allow associating any given User Stories one or more Sprints, as needed. You can add as many Labels to a given Issue as you wish.

**What to do**: Each team must have a set of Labels to represent each Sprint within GitHub's Issues tracker:

- `Sprint 0`
- `Sprint 1`
- `Sprint 2`
- `Sprint 3`
- `Sprint 4`

Once a particular Sprint has begun, all Issues representing User Stories, Tasks, or Spikes that have been decided to be addressed within that Sprint must be assigned to the proper Label representing that Sprint.

## Creating releases

It is customary to issue a new product **Release** at the end of each Sprint. This can be accomplished from within GitHub by clicking the `Create a new release` link from the main repository page.

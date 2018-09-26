# Contributor Summit Project Template

Contributor Summit project month is an experimental new format that builds on hack
sessions from past Contributor Summits and refocuses on long-term sustainability.
We're hoping that not only do you get a supported chance to play with some of our
new technology, but you can build it into something that contributes to the larger
DevOps community. We'll kick things off at Puppetize Live and make our first
releases at Contributor Summit Online, so this is a month-long hackathon!

There are only two restrictions on what projects you can choose:

1. You must be able to complete an MVP release in one month.
1. The project must contribute something positive to the world of DevOps.

This means that your project could be anything from a Puppet module, to a CI or
testing framework, to enhanced documentation for another project, to a process or
pattern proposal. The possibilities are endless!

Puppet will facilitate your effort during the event to help keep you from getting
blocked on some common issues and to keep your project moving along quickly. We
won't have a lot of time, so we'll all have to work effectively. See below for some
examples of resources that you will have access to.

We're glad that you're joining us on this adventure. It will be fun!

# Getting Started
It's easy to get going. We'll ask that you follow these steps and work from this
repository because it will make it much easier for us to keep track of who's working
on what projects and what your status is.

[GitHub has a useful tutorial](https://help.github.com/articles/fork-a-repo/) if you
need help with any of these steps.

1. Start off by creating a free GitHub account, if you don't already have one.
    * https://github.com/join
1. Fork this repository to your own namespace by clicking the *Fork* button in
   the top right of this page.
    * Remember to fork to your own namespace if you're a member of one or more organizations.
1. Now `clone` the repository to your own workstation.
    * Open your terminal window and navigate to the directory where you'd like to keep
      the local copy of your repository.
    * Run the command `git clone https://github.com/<your username>/contributor-summit-project`
1. Run the setup script to populate issues and milestones.
    * Windows
      1. Install a Ruby runtime if needed.
          * https://rubyinstaller.org
      1. Run the command `./setup.ps1`
    * Linux/Mac
      1. Install Ruby following your distribution's standards if needed.
      1. Run the command `./setup.rb`
 1. Email your project information to community-team@puppet.com. Include:
      1. Your name
      1. Your Slack username
      1. Your [project charter](../../issues/1)
      1. The URL to this repository

## Using GitHub features
GitHub includes some optional repository features that you might be interested in.
Open the [Options](../../settings) page to check them out.

### GitHub Wikis
You might choose to keep your project documentation in a Wiki to enable low-friction
collaborative editing. If you're creating a Puppet Module, you should use the
standard `README.md` and `REFERENCE.md` [documentation pattern](https://puppet.com/docs/puppet/latest/modules_documentation.html) instead.

Reference the [GitHub documentation](https://help.github.com/articles/about-github-wikis)
if you'd like more information.

### GitHub Projects
Project boards help you organize and prioritize your work. They are made up of issues,
pull requests, and notes organized as cards in columns. You can drag and drop the
cards and columns as needed. Get started by enabling the feature, then creating a new
board. Starting from a basic Kanban template will likely be the easiest way to get started.

Reference the [GitHub documentation](https://help.github.com/articles/about-project-boards)
if you'd like more information.

# Resources Provided
We would like to help ensure your success. We'll be working with you to help keep your
projects on track. We'll help you define your project scope and set roadmap goals, then
check in with you roughly weekly. (Milestones are scheduled for each Wednesday, but the
actual checkin date & time will vary.) In addition, during the project month we'll provide
several resources and services that you might not otherwise have access to.

Some of the resources will be provided via webinars or by downloaded materials and some
will be provided in one-on-one chats or video consulations. The Puppet community team
will coordinate with each of you to ensure that you receive all the help you need.

<insert resource list>

# Project Ideas
If need a little inspiration to come up with a project idea, we've put together a 
[list of some suggestions](../../PROJECTS.md). Feel free to use what you'd like from here,
no credit is needed.

# Questions?

* Can I work on an existing project?
   * Sure! It would help us keep track of projects if you forked this repository and
     add your charter and a link to the actual project repository as the `README.md`. 
* Can I work on something that's not software?
   * Absolutely. Use this month to write a DevOps book, if you'd like! As you're defining
     your roadmap, you'll want to massage the issue queue to be more useful for the kind
     of project you want to work on.
* How will we communicate during the project month?
   * Project coordinators will contact you via email or Slack.
   * The [Puppet Community Slack](http://slack.puppet.com) has a #contributor-summit channel for conversation.
   * Email community-team@puppet.com if you need anything.
* What if I can't run the setup script?
   * The script just turns on the Issues queue and clones the milestones and issues from
     the template repository. You can do that manually if needed.
* What if I have other questions?
   * Email community-team@puppet.com.


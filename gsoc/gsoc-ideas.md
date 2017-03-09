# Google Summer of Code

This is the ideas page for EDGI's Google Summer of Code (GSoC) program!

All newcomers to the project should review our [project introduction](https://github.com/edgi-govdata-archiving/overview/) to learn more about where and how we work. Our repositories can be found on our [Github organization page](https://github.com/edgi-govdata-archiving/).

**Important Note**--to learn how to contribute to EDGI software, see our [Contributing Guidelines](https://github.com/edgi-govdata-archiving/overview/blob/master/CONTRIBUTING.md).

## Contact Us

Most development communication happens on [archivers.slack.com](https://archivers.slack.com/), where anyone can [request an invite](https://archivers-slack.herokuapp.com/). Please introduce yourself in `#gsoc` rather than in #general, as we have a lot going on in the Slack team! Matt Price ( [@titaniumbones](https://github.com/titaniumbones) | @mattprice) is the technical lead for the project.

For project-related topics, reach out on Slack — either in `#gsoc` or in the appropriate development channel — or file an issue in the appropriate Github repo.

For GSoC application inquiries, use the `#gsoc` channel.

Please note that our project has a weekly rhythm. The first half of the working week (Monday-Wednesday) is usually the best time for our core volunteers to think about new feature development and onboard new participants. Thursdays and Fridays we are often busy preparing for [weekem events](https://envirodatagov.org/events/), and on weekends we are either supporting events or recovering from them. Please be patient and/or self-directed during our busy periods!

## Contribute Improvements

We have [preferred guidelines](https://github.com/edgi-govdata-archiving/overview/blob/master/CONTRIBUTING.md) for submitting changes. Please read them over!

We also love it when students show that they are excited to work with us by looking at some of our `first-timer` issues in our [**web-monitoring**](https://github.com/edgi-govdata-archiving/web-monitoring) or [guides](https://github.com/edgi-govdata-archiving/guides/labels/first-timer) repos and even submitting a pull request! This gives us confidence that you've read our contribution guidelines and would be ready to jump into a project.

## Submit a Proposal!

If you are interested in being a [GSoC student](https://summerofcode.withgoogle.com/get-started/) with us, first read through our organization profile, join the `#gsoc` channel in our slack, and tell us what you're interested in working on and a bit about your experience.

It's also great to hear if you've forked one of our codebases and set up a development environment. Done with that? How about running tests? Tell us how far you've gotten!

Once your idea is more developed, please submit a PR to [`overview/gsoc`](https://github.com/edgi-govdata-archiving/overview/blob/master/gsoc) with the name `proposal-familyname-firstinitial.md` describing your proposal in detail based off of the [template](https://github.com/edgi-govdata-archiving/overview/blob/master/gsoc/gsoc-template.md) for proposals. Any questions on the process can go in `#gsoc`!

# Potential Ideas

## Apply Machine Learning to Monitoring Website Changes
- **Part of:** [**web-monitoring**](https://github.com/edgi-govdata-archiving/web-monitoring) 
- **Description:** Help us improve our government agency website monitoring through the use of machine learning in order to reduce the amount of unnecessary review our analysts perform during computer-assisted identification of important changes. 
- **Contact:** `#dev-webmonitoring` on [archivers.slack.com](https://archivers.slack.com/) 
- **Keywords:** new features, machine learning, data analysis, visualization
- **Ideal Experience and Interest:** Python, Ruby on Rails, [Node.js](https://nodejs.org/en/), Machine Learning (in particular [scikit-learn](http://scikit-learn.org/stable/index.html)). 

The web-monitoring project has had 4 months of development and interacts with the API from our partner organization to pull down and compare changes in versions of webpages on the domains we monitor. We are looking to move into supporting the analyst's task of comparing and determining important changes through the application of machine learning (ML) models. This is a very new project which will evolve rapidly in March and April. Right now, the best way to begin is by: 
  - reviewing the documentation from the [Web Monitoring project](https://github.com/edgi-govdata-archiving/web-monitoring), as well as the [web-monitoring-processing codebase](https://github.com/edgi-govdata-archiving/web-monitoring-processing). 
  - examining and contributing to some of the issues related to ML:
      - [Machine Learning Requirements Issue](https://github.com/edgi-govdata-archiving/web-monitoring-processing/issues/21)
      - [Create Sample Dataset for Machine Learning](https://github.com/edgi-govdata-archiving/web-monitoring/issues/6)

## Refine Event-based Preservation Application

- **Part of:** [archivers.space app](https://github.com/edgi-govdata-archiving/archivers.space) and [harvesting-tools](https://github.com/edgi-govdata-archiving/harvesting-tools)   
- **Description:** We have a backlog of feature requests and a growing application to handle event-based preservation and data downloading. Features we're keen for include improving our leaderboard so we can see how volunteers are doing at events, making our interface cleaner and easier to understand, and more.   
- **Contact:** `#dev-archivers-space` on [archivers.slack.com](https://archivers.slack.com/)   
- **Keywords:** new features, optimization, security, web application, visualization
- **Ideal Experience and Interest:** JavaScript ([Meteor](https://www.meteor.com/), [Node.js](https://nodejs.org/en/)), Heroku, AWS, [MongoDB](https://www.mongodb.com/)

Our pipeline app and harvesting-tools are the most mature of our projects, but have a fair bit of refining before they are really stable. Also-- we've got ongoing research and questions around best practices in web security. We have short cycles of development, use, feedback, and refinement so if you are interested in learning more about web application security and development in an agile-inspired development process this might be for you!

## Propose your own!

# Scalable Education Model

## Overview

Open-source and the related workflows are one of the most successful models for collaboration that have ever been applied. Combining open-source with a [distributed version control](http://en.wikipedia.org/wiki/Distributed\_revision\_control) such as Git allows for a true peer-to-peer approach to collaboration that is unlike anything that came before.

Applying the same principles and workflows to education is one of the best ways to create a sustainable proliferation of high-quality curriculum spread across the world. Leveraging many of these principles will ensure quality and integrity of the experience is maintained as the content is reproduced and propogated.

### Open-Source

**What is open-source as a model?**

Open-source software is software whose source code is published and made available to everyone, enabling anyone to copy, modify and redistribute the source code without paying royalties or fees. Open-source code can evolve through community cooperation. These communities are composed of individual people as well as large organizations. Some of the individual people who start an open-source project may end up establishing companies offering products or services incorporating open-source programs.

**How do people collaborate in open-source?**

Open-source software is developed in cooperation between many different individuals all working together with a specific structured workflow to enable mass collaboration. For example, the [Linux](http://www.linux.com/) project has roughly **10,000** people that have contributed to the core alone. Another 100,000+ have contributed to software built in "user-space" surrounding the Kernel itself.

When building software or curriculum coordinating even 10 collaborators can be immensely challenging. In order to solve this problem, open-source generally adopts structured solutions to make cooperation much easier. These solutions more recently include the use of a distributed version control system called Git.

To understand open-source, we have to understand the different roles involved in coordinating collaborators helping on a project:

1. **Creator** (a.k.a Benevolent Dictator) - This is the person that originally created the project or a spiritual successor that has final decision making power on the "official" content repository.
2. **Core Maintainers** - This is the team that can write to the official content repository. The stewards of the project responsible for maintaining the quality and integrity of the project.
3. **Contributors** - These are people interested in contributing to the content repository and they do so by "forking" a personal clone of the repository in which they make changes and then later submit for review by maintainers.
4. **Commenters** - These are people that haven't yet contributed to the content itself but raise issues when they come up, comment on discussions taking place, and actively provide their feedback on the decisions made on the project.

![](http://git-scm.com/book/en/v2/book/05-distributed-git/images/integration-manager.png)

The process workflow is generally as follows:

* The core project maintainers push to a shared public repository ("blessed remote").
* A maintainer or a commenter raises an issue for discussion
* A contributor clones the blessed repository and makes changes to their clone.
* The contributor pushes to their own public clone online.
* The contributor sends the maintainer a "pull request" asking them to pull the changes.
* The maintainers, contributors and commenters discuss the changes.
* The maintainer adds the contributor’s repo as a remote repo and merges locally.
* The maintainer pushes merged changes to the main repository after careful review.&#x20;

### Education and Open-Source

Let us attempt to apply the successful open-source model to education and curriculum worldwide. A few key attributes need to be emphasized:

* **Decentralized** - No single point of failure. Collaboration and propagation is peer-to-peer with "maintainers" and "contributors" working together to ensure quality.
* **Free from Restriction** - Anyone is free to copy, modify and redistribute the source code without paying royalties or fees. People can freely branch off and use the content for any purpose at any time without permission from the maintainers.
* **Transparency** - Open-source allows for high-quality content to thrive not by restricting use but through absolute transparency. Every version of the content is available for all to see. The authors of the content can be viewed as well. Any information relating to the effects or usage of the content is completely visible to everyone.

Applying open-source to education is a fundamental shift in how the world thinks about learning and teaching. A few examples of how to think about an open-source education model in practice:

* **Living Textbooks** - All learning materials are entirely free and managed by maintainers world-wide. Maintainers help curate and edit the content and ensure that the quality is as high as possible. Think [Wikipedia](https://en.wikipedia.org/wiki/Main\_Page) for every single topic out there. These textbooks can be "branched" out by anyone into new versions or new collaborators can request their changes to be pulled back into the core.
* **Living Courses** - All course structure and materials are entirely free and managed by maintainers world-wide. The maintainers are constantly working together to improve the course materials and structure. Assignments, resources, videos, guides, etc. are all available for online for easy access and modification.&#x20;
* **Living Tools** - Courses are powered by open-source software tools and frameworks that enable everyone to have a consistent experience. The learning management system itself is completely free and open-source. Any "content modules" developed through collaboration can be easily plugged into the course content tools which provide rich access to the textbooks and course materials.
* **Transparent Analytics** - Open-source education must be paired with transparent analytics around efficacy. This is in part measured by assessments and surveys baked into the course content that are submitted by everyone that participates in a learning module. These analytics help maintainers and collaborators to understand the most effective content modules.
* **Distributed Classrooms** - Since the tools, the courses, and the textbooks are entirely free to access and to redistribute, classroom "peers" will pop-up without any friction. A classroom is defined as a location where there are a number of individuals that would like to learn the material as well as an "instructor" (or facilitator) that helps locate a physical venue and create a safe and productive space for interested students to meet and run through the course.

Imagine a world where this was considered the gold standard for all topics of education. Millions of people working to review and contribute to countless course modules and textbooks. Classroom analytics allowing everyone to focus their efforts where the strongest impact is being made. Students world-wide self-organizing around facilitators and learning together in millions of small distributed peer groups.

## Open Questions

* How do we make it easy for different versions to be easily discoverable. For example, highest rated Android curriculum vs highest rated Android curriculum to teach K-12 vs highest rated curriculum to teach k-12 with advanced CS knowledge. I think we need to moderate how curriculum can be described. Calling a curriculum beginner is not specific enough to let instructors know who will do well in the class.
* How do you easily bake measurement into the system while still allowing for flexibility?

## References

* [Open Business Model Free Education](http://opensource.com/education/13/10/open-business-model-free-education)
* [Dictator and Lieutenants Workflow](http://git-scm.com/book/en/v2/Distributed-Git-Distributed-Workflows#Dictator-and-Lieutenants-Workflow)
* [opensource.com/education](http://opensource.com/education)
* [Richard Baraniuk On Open Source Learning](http://www.ted.com/talks/richard\_baraniuk\_on\_open\_source\_learning?language=en)

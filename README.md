# Design & Development Challenge IDP

Pasteur Labs architecture — 1-week home assessment :)

Task description: <https://drive.google.com/file/d/1_1gh4IgMbkRySBGwKTAzYRmk7g-6Zs6Z/view?usp=sharing>

### Legends

-   Platform — Internal Developer Platform (IDP)

-   Team/Teams/Users — users of the Platform, Research Engineers, Scientists of any kind (not necessarily with programming background)

-   Keepers — IDP team

Overview
========

The objective is to develop a Platform designed to streamline the endeavors of Teams engaged in scientific research. This encompasses areas that demand intensive computations, such as artificial intelligence algorithms (including Machine Learning, Deep Learning, Reinforcement Learning, etc.) and scientific simulations spanning disciplines like physics, biology, sociology, and beyond.

### What Should the Platform Be?

The Platform should embody simplicity and strength, acting as a foundation akin to the straightforward design of an AK-47 combined with the robustness of concrete. It's designed to underpin further developments that enhance team efficiency and elevate happiness levels among Teams members.

Key components of the Platform include:

-   Resources: A compilation of handy libraries, tools, and APIs that drive innovation and ease-of-use.

-   Templates: These aim to standardize and simplify interactions with cloud providers and other third-party services. They come with embedded best practices, security protocols, and adherence to regulatory requirements.

-   Services: Turnkey solutions curated and upheld by the Platform, accessible to all Teams irrespective of their specific tasks. These services might be constantly online or instantiated on demand.

Example: Utility snowflake services, such as UUID generators.

-   Guides: Clear "How-to" step-by-step guidelines enabling Teams to kick-start operations swiftly, even in the absence of DevOps expertise.

-   Best Practices: These are either integrated into templates or presented as informative articles, providing teams with the knowledge to excel.

-   Intuitive User Interfaces: Comprehensive web UIs equipped with features for tasks that are repetitive, require meticulous adjustments, or are infrequently used.

Examples: Credential generators, local playground container deployments, template generators, AutoML tools, and more.

-   ...and More: The Platform remains agile, ever-adapting to cater to evolving needs.

### What Should the Platform NOT Be?

The Platform should not devolve into a rigid framework that encumbers Teams. It must avoid:

-   Overbearing instructions that stifle creativity and innovation.

-   Arbitrary demands that don't align with the goals or needs of the teams.

-   Imposition of specific technologies without clear justification or benefit.

-   Its essence should be to empower and facilitate, not to restrict or dictate.

Users
=====

The Platform is crafted with Teams at its core, tailored to cater to their needs. It's essential to remember that the Teams are not subservient to the Platform; rather, the Platform exists to serve them.

At the heart of it, all are the Users. They stand as the primary source of truth and the fountainhead of requirements. However, these requirements and feedback are thoughtfully vetted by the vigilant and discerning Platform Keepers, ensuring that the Platform remains efficient, effective, and user-focused 🙂

### Relationship

-   Understanding Needs: Keepers must work in tandem with Teams to deeply understand their requirements and challenges. This collaborative approach ensures the Platform evolves in tandem with user needs.

-   Keeper-Team Dynamics: Keepers should regard Teams as valuable clients, much like those in the market who invest money in a product. This mindset encourages a high level of service and understanding. Teams are not just fellow programmers; they deserve comprehensive explanations and guidance where needed.

-   Role of Keepers: Teams should view Keepers as allies — individuals ready to assist with a diverse array of challenges, be it through turnkey solutions or just sage advice.

-   Perception of the Platform: While the Platform offers a vast array of tools and resources, Teams shouldn't perceive it as a "one-size-fits-all" solution. Instead, they should recognize it as a sturdy foundation upon which they can build, adapt, and innovate.

This mutual understanding and respect lay the groundwork for a productive and harmonious relationship.

Key Directives:

-   Open Communication: Encourage an ongoing dialogue and joint discussions between Keepers and Teams. It's imperative to steer clear of "toss-and-forget" situations where feedback or requests are ignored or left unaddressed.

-   Purposeful Documentation:

-   Craft documentation with a primary focus on genuine utility, rather than merely satisfying bureaucratic requirements.

-   Recognize that documentation serves as an integral part of the Platform.

-   Aim for clarity, making it accessible even to potential external clients. Docs should be a gateway to new features, not a boastful wall saying, "Too smart for you, so move along."

-   Comprehensive Guides:

-   Provide step-by-step guidelines across all resources — be it libraries, documentation, or best practice articles.

-   Ensure these guides remain current, reflecting the latest changes and updates.

-   Intuitive User Interface:

-   Implement a user-friendly graphical interface where it adds genuine value, especially when users need to adjust multiple parameters.

-   However, balance is crucial — avoid over-complicating the UI when tasks could be accomplished more swiftly via the Command Line Interface (CLI).

-   Promoting Best Practices: Disseminate best practices either through detailed articles, succinct guides, or even curated links to reputable sources on the web. This ensures Teams always have access to the best knowledge available.

### Portal

The journey of a new Team in the company should start with a central web portal with all docs, guides, UIs, and catalogs of links in one place.

Standardization and Unification (exploit)
=========================================

This chapter is about conservative forces in the Platform. The exploitation part of the exploration-exploitation dilemma.

Trying to fix the foundation of a half-built house is a recipe for disaster.

The Platform should be built on industry-proven and time-tested solutions. Experiments and untested innovations are not welcomed. This approach will prevent system failures that could potentially impact all the Teams in the company simultaneously.

Points:

-   Team Productivity: Addressing issues on the Platform can significantly hamper Teams productivity.

-   High Costs and Re-architecture: Some fixes might be so costly that they necessitate a complete re-architecture of the solution. Such an overhaul could spell disaster for the company.

-   Company Reputation: Even minor glitches with the Platform that affect client satisfaction can tarnish the company's reputation. For a fledgling startup, this could be the tipping point toward failure.

### Unification

Teams should be motivated to adopt the same technology whenever feasible. Take, for instance, the choice of text editors. Despite the multitude of options available, adopting a singular platform like VS Code allows for the development of specialized tools and plugins tailored for that specific editor, eliminating the need to spread resources thin across multiple platforms.

This approach not only enhances efficiency but also ensures consistent tooling across the team.

### Standardization

Teams should be incentivized to adhere to established best practices and utilize templates, libraries, and other resources provided by the Platform. Adopting this standardized approach accelerates and streamlines the Platform's expansion. For instance, when new regulatory requirements arise, they can be implemented uniformly and swiftly across the board.

Standardization ensures consistency, reduces potential errors, and simplifies both maintenance and updates.

### Procedure of acceptance

To qualify for inclusion in the Platform, new technology must meet the following criteria:

-   Market Presence: How long has it been on the market?

Ex.: Kubernetes was released in 2014.

-   Relevance: Is it still actively used and supported in the industry?

Ex.: All major cloud providers offer k8s services.

-   Integration: Can it be integrated into the Platform as an extension without altering the core?

Ex.: To support a new cutting-edge cloud provider, it should merely require adding new templates and adapters.

-   Team Testing: Has it been intensively tested by at least one of the Teams?

-   Essentiality: Is the technology so fundamental that the work of all teams would be rendered ineffective without it?

-   Consensus: Is there a unanimous decision to adopt the technology, even if it involves risks?

### Overall

Pros:

-   Rapid Development: Accelerated development of the Platform by leveraging industry-leading, battle-hardened solutions rather than creating our own.

-   Reliability: Enhanced Platform stability by adopting proven technologies.

-   Best Practice Adoption: The ability to seamlessly integrate the latest best practices through standardized tools.

-   Efficiency: Avoid the pitfalls of reinventing the wheel. Opting for specialized third-party services, even if expensive, can be more efficient if they're successful, market-tested, and time-proven.

-   Focused Effort: The simplicity of employing a single technology reduces effort dispersion across various targets.

Cons:

-   Rigidness

Flexibility (explore)
=====================

This chapter is about liberal forces in Platform. The exploration part of the exploration-exploitation dilemma.

A platform for scientists working on the cutting edge of humanity discovery that doesn't welcome innovation? Is this a joke?

The Platform is not just a static entity but a dynamic foundation. It's designed to facilitate the endeavors of Teams, to mold and adapt, reflecting the multifaceted requirements they bring to the table. With an ideal setup, each Team is equipped with a dedicated DevOps engineer, ensuring that they can shape and customize solutions seamlessly atop this foundation.

When a particular technology has been rigorously vetted by a Team and garners positive reviews, it doesn't remain confined to that unit. Instead, it's integrated as a core feature, available for the broader community of Teams.

We're always on the lookout for technologies that enhance the Platform's malleability, scalability, and versatility. To name a few examples:

-   Infrastructure as Code: extensible templates, like Terraform, which come equipped with industry-recommended configurations.

-   Configuration as Code: Ensuring consistent environments and setups, minimizing discrepancies and errors.

-   Pipeline as Code: pipelines aren't just about deployment. They come pre-loaded with security and compliance checkpoints, underscoring our commitment to robust operations.

Platform as a Product
=====================

The Platform should not be a one-time project but rather an evolving product. As such, all modern methodologies, such as Agile, should be applied to its development. Implementing consecutive steps that provide immediate value is crucial. In the initial phases, close collaboration with teams is essential to gather requirements and feedback.

For a startup, focusing all efforts on a viable Minimum Viable Product (MVP) is crucial. It allows the startup to quickly test its core hypothesis in the market and iterate based on real user feedback.

In the future, Platform could be commercialized for external use, potentially forming the foundation of a full-blown business.

Details
=======

### Kubernetes

-   Cloud native architecture.

-   Portable. Could be used on-prem and migrated to the cloud easily.

-   Multi and hybrid cloud.

-   Abstract deployment.

-   Vendor locking.

-   Potentially use Kubernetes clusters as a supercomputer.

### GitOps

-   Version control.

-   Pull Deployment (FluxCD).

-   Rollback, git revert.

-   Single source of truth.

-   Security since only Flux needs access to a git repo.

### Kubeflow

-   <https://www.youtube.com/watch?v=G7zW1Wqym00> 

-   Supported by all providers.

-   Supports all frameworks.

-   Web interface.

### Slurm

-   Workload manager for supercomputers.

-   Widely supported.

-   The platform is highly scalable and resilient.

-   Used on HPC clusters.

### HPC

-   Azure Cyclecloud, Azure Batch

-   Slurm can easily be enabled on a CycleCloud cluster

### DVC

-   <https://www.youtube.com/watch?v=UbL7VUpv1Bs>

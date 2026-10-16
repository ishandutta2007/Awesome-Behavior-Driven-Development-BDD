# Awesome-Behavior-Driven-Development-BDD

## Top Behavior-Driven Development (BDD) Ecosystem



**Curated List of SaaS Products & Open-Source GitHub Projects**  

*Focused on Gherkin Specifications, Step Definitions & Living Documentation*  

**Last updated: October 2026**



This repository tracks notable **SaaS platforms** and **open-source projects** for **Behavior-Driven Development (BDD)**. These tools enable teams to write executable specifications in plain language, bridge the gap between business stakeholders and engineers, and turn acceptance criteria into automated tests that serve as living documentation.



**Examples** include SpecFlow, Cucumber, Reqnroll, Behave, Gauge, Tricentis Tosca, Micro Focus UFT, Katalon Studio, Testsigma, and QASymphony (the category leaders).



**Open-source emphasis**: This section is heavily expanded with every major active project for self-hosting, Gherkin execution, and open BDD frameworks—ideal for QA engineers, product teams, and developers seeking transparent, vendor-independent specification testing.



Contributions welcome! Open a PR to add/update entries. Keep descriptions factual and link to official sites.



## Table of Contents

- [SaaS/Hosted Platforms](#saas-hosted-platforms)

- [Open-Source GitHub Projects](#open-source-github-projects)

- [How to Contribute](#how-to-contribute)

- [Disclaimer](#disclaimer)



## SaaS/Hosted Platforms

| Platform | Company / Owner | Company Size (Revenue / Valuation) | Pricing (Starting Tier) | Free Tier Limits / Trial Limits | Description |
|---|---|---|---|---|---|
| **[Micro Focus UFT (OpenText)](https://www.microfocus.com/)** | OpenText | $5.25B revenue (FY24, Public: OTEX) | Starts at ~$3,200/seat/year (~$267/month) | No free tier; 30-day proof-of-concept (PoC) evaluation license available upon request | Enterprise standard for functional test automation and Gherkin BDD in enterprise & regulated environments. |
| **[Tricentis Tosca](https://www.tricentis.com/)** | Tricentis | $4.5B valuation | Starts at ~$20,000/year (~$1,667/month base deployment) | No permanent free tier; 14-day free trial with access to core test automation & model-based modules | Enterprise continuous testing platform offering model-based automation and BDD support. |
| **[QASymphony (Tricentis qTest)](https://www.tricentis.com/products/qtest/)** | Tricentis | $4.5B valuation | Starts at ~$50–$90/user/month (or ~$1,000/user/year) | No permanent free tier; 14-day free trial across qTest Manager, Sessions, Explorer, and Pulse modules | Test management platform with BDD support via qTest Scenario, requirements traceability, and Jira integration. |
| **[Gauge Cloud](https://gauge.org/)** | ThoughtWorks | $1.13B revenue (Apax Partners) | Free (Core engine is 100% open-source Apache 2.0; cloud runner costs depend on cloud infra) | Free forever (100% open-source tool; unmetered local test authoring and execution; infrastructure usage billed by cloud provider) | Markdown-based test specification and living documentation framework developed by ThoughtWorks. |
| **[CucumberStudio](https://cucumber.io/)** | SmartBear | ~$500M+ revenue | Starts at $32/user/month (Starter cloud tier) | No permanent free tier for studio; 14-day free trial with full feature collaboration and test management access | Collaborative BDD platform providing feature file editing, test execution tracking, and living documentation hosting. |
| **[Katalon Studio](https://katalon.com/)** | Katalon | ~$40M–$60M ARR | Starts at $84/user/month (Professional plan, billed annually) | Free forever plan: restricted to local test authoring/manual execution, no CLI/CI-CD pipeline execution without paid KRE add-on | Comprehensive test automation platform with native BDD feature files and Groovy step definitions. |
| **[Testsigma](https://testsigma.com/)** | Testsigma | ~$5M–$10M ARR ($18M funding) | Starts at $8/user/month (Test Management Pro) / $14/user/month (AI Suite) | Free forever plan for test management (basic tier); 14-day free trial for Cloud Test Automation platform | AI-driven continuous test automation platform featuring codeless NLP test authoring and BDD execution. |



## Open-Source GitHub Projects



- **[Cucumber (cucumber-js)](https://github.com/cucumber/cucumber-js)**  

  **Behavior Driven Development (BDD) testing framework** (MIT) . **The JavaScript/TypeScript implementation of Cucumber** . **The reference implementation of the Gherkin language** . **Features**: **Plain-text feature files** written in Gherkin syntax (`Feature`, `Scenario`, `Given`, `When`, `Then`, `And`, `But`), **step definitions** that map Gherkin steps to executable code, **hooks** for setup/teardown (`Before`, `After`, `BeforeStep`, `AfterStep`), **tags** for selective execution, **data tables and doc strings** for complex inputs, **world** object for sharing state across steps, and **parallel execution** support . **Integrates with all major JavaScript test runners**—Jest, Mocha, Vitest, and Playwright . **Used by teams worldwide** for acceptance test-driven development (ATDD) and specification by example .



- **[Reqnroll](https://github.com/reqnroll/Reqnroll)**  

  **The official successor to SpecFlow for .NET BDD** (MIT) . **SpecFlow was discontinued by Tricentis** —Reqnroll is the community-driven fork that continues development. **The .NET BDD standard in 2026** . **Features**: **Gherkin feature files**, **step definitions in C#**, **dependency injection support**, **hooks**, **tags**, **scenario outlines with examples**, **parallel execution**, and **comprehensive reporting** . **Migration from SpecFlow is straightforward**—the API is intentionally compatible .



- **[Behave](https://github.com/behave/behave)**  

  **BDD framework for Python** (BSD-2-Clause) . **The Python implementation of Cucumber/Gherkin** . **Features**: **Gherkin feature files**, **step implementations in Python**, **environment hooks** (`before_all`, `after_all`, `before_feature`, `after_feature`, `before_scenario`, `after_scenario`, `before_step`, `after_step`), **tag-based filtering**, **data tables**, **scenario outlines**, **parallel execution via behave-parallel**, and **formatters** for JUnit, JSON, and pretty output . **The standard BDD framework for Python** .



- **[Behat](https://github.com/Behat/Behat)**  

  **BDD framework for PHP** (MIT) . **The PHP implementation of Cucumber/Gherkin** . **Features**: **Gherkin feature files**, **step definitions in PHP**, **hooks**, **tags**, **scenario outlines**, **Mink integration** for browser automation, and **extensions system** . **The standard BDD framework for PHP** .



- **[Gauge](https://github.com/getgauge/gauge)**  

  **Lightweight cross-platform test automation tool** (Apache-2.0) . **Markdown-based specifications**—less ceremony than Gherkin, more readable for business stakeholders . **Features**: **Markdown specs**, **multiple language runners** (Java, JavaScript, Python, Ruby, C#, Go), **data-driven execution**, **parallel execution**, **plugins** (HTML report, XML report, screenshots, IDE support), and **living documentation** . **The most pragmatic BDD tool for teams that find Gherkin too verbose** .



- **[JBehave](https://github.com/jbehave/jbehave)**  

  **BDD framework for Java** (BSD-3-Clause) . **The original Java BDD framework**—predates Cucumber-JVM . **Features**: **Gherkin-like stories**, **step definitions**, **embedders** for JUnit, Spring, and others, **pending steps**, and **story reporting** . **The foundation for Java BDD** .



- **[Cucumber-JVM](https://github.com/cucumber/cucumber-jvm)**  

  **Cucumber for the JVM** (MIT) . **The Java implementation of Cucumber/Gherkin** . **Features**: **Gherkin feature files**, **step definitions in Java/Kotlin/Groovy/Scala**, **dependency injection** (Spring, Guice, PicoContainer, CDI), **hooks**, **tags**, **parallel execution**, and **JUnit/TestNG integration** . **The standard BDD framework for the JVM** .



- **[Cucumber-Rust](https://github.com/cucumber-rs/cucumber)**  

  **Cucumber for Rust** (MIT/Apache-2.0) . **The Rust implementation of Cucumber/Gherkin** . **Features**: **Gherkin feature files**, **async step definitions with Tokio**, **scenario state management**, **attribute macros**, and **custom world** . **The standard BDD framework for Rust** .



- **[Karate](https://github.com/karatelabs/karate)**  

  **Unified test automation framework** with BDD syntax for API testing (Apache-2.0) . **The most popular BDD tool for API testing** —write tests in Gherkin-like syntax without step definitions. **Features**: **API testing**, **UI testing**, **performance testing**, **mocking**, **parallel execution**, and **HTML reports** . **The fastest path to BDD for API testing** .



- **[Concordion](https://github.com/concordion/concordion)**  

  **Open-source tool for writing executable specifications in Java** (Apache-2.0) . **The most "specification by example" native tool**—surrounds executable examples with prose descriptions . **The closest thing to truly readable specifications that are also tests** .



### Additional Strong Open-Source Options



- **[pytest-bdd](https://github.com/pytest-dev/pytest-bdd)** — BDD library for pytest (MIT) . **The most Pythonic approach to BDD**—uses pytest fixtures and markers instead of Behave's environment model .

- **[Cucumber.js Playwright](https://github.com/cucumber/cucumber-js)** — Cucumber + Playwright integration for browser automation in JavaScript/TypeScript .

- **[Serenity BDD](https://github.com/serenity-bdd/serenity-core)** — Open-source library for writing BDD acceptance tests (Apache-2.0) . **The most comprehensive Java BDD reporting framework** .

- **[SpecFlow (legacy)](https://github.com/SpecFlowOSS/SpecFlow)** — The original .NET BDD framework (MIT) . **Discontinued by Tricentis** —migrate to Reqnroll .

- Community **n8n** workflows for test execution orchestration and BDD report routing.



**Frameworks for building custom systems**: Combine **Cucumber-JVM** for JVM BDD with **Reqnroll** for .NET, **Behave** or **pytest-bdd** for Python, **Karate** for API testing, and **Gauge** for Markdown-based specifications—creating a comprehensive cross-language BDD testing stack.



## How to Contribute



1. Fork the repo.

2. Add/edit entries in `README.md` (follow existing format).

3. Include: name, link, 1–2 sentence description, and whether it's SaaS or open-source.

4. Submit PR with a short explanation.



Star the repo if you find it useful!



## Disclaimer



- This is a **community-curated** list — not exhaustive and not an endorsement.

- BDD frameworks handling test specifications must comply with data protection regulations (GDPR, CCPA, etc.) and avoid including real credentials or PII in feature files.

- **Open-source BDD is mature and production-ready.** Cucumber-JVM, Behave, Behat, and SpecFlow/Reqnroll are the established implementations for their respective languages . Karate is the standard for API BDD testing . Gauge offers a pragmatic alternative to Gherkin . **These are genuine alternatives to commercial platforms.**

- **SpecFlow is discontinued.** **Reqnroll is the official successor** for .NET BDD—the community-driven fork that continues development with an intentionally compatible API . **Migrate existing SpecFlow projects to Reqnroll.**

- **Gherkin is a language, not a religion.** Gauge's Markdown-based specs offer less ceremony and more readability for business stakeholders . Karate eliminates step definitions entirely for API testing . **Choose the level of ceremony that your team actually benefits from.**

- **Step definitions are maintenance burden.** Every Gherkin step requires a matching step definition—this is the hidden cost of BDD. **Keep step vocabulary small and focused** to avoid combinatorial explosion of step definitions.

- **BDD is about collaboration, not tools.** The tooling is secondary to the conversation between business, development, and QA. **Tools without the conversation produce the same testing problems with more ceremony.**

- Self-hosted open-source solutions require proper CI/CD integration, test environment management, and ongoing maintenance. **Feature files are code**—they belong in version control alongside the application.



---



**Made for QA engineers, product teams, and developers building transparent BDD testing solutions.**  

Let's make Behavior-Driven Development more open, data-driven, and executable.

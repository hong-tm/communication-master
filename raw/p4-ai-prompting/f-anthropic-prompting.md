Title: Prompt engineering overview

URL Source: https://docs.claude.com/en/docs/build-with-claude/prompt-engineering/overview

Markdown Content:
[Claude Platform Docs](https://docs.claude.com/docs/en/home)
*   [Messages](https://docs.claude.com/docs/en/intro)
*   [Managed Agents](https://docs.claude.com/docs/en/managed-agents/overview)
*   [Admin](https://docs.claude.com/docs/en/manage-claude/admin-api)
*   
Resources
    *   [Best practices](https://docs.claude.com/docs/en/about-claude/use-case-guides/overview)
    *   [Models & pricing](https://docs.claude.com/docs/en/models/overview)
    *   [SDKs, CLI, and libraries](https://docs.claude.com/docs/en/cli-sdks-libraries/overview)
    *   [Claude API skill](https://docs.claude.com/docs/en/agents-and-tools/agent-skills/claude-api-skill)
    *   [Release notes](https://docs.claude.com/docs/en/release-notes/overview)

[API reference](https://docs.claude.com/docs/en/api/overview)

English

[Console](https://docs.claude.com/)[Log in](https://docs.claude.com/login?returnTo=%2Fdocs%2Fen%2Fbuild-with-claude%2Fprompt-engineering%2Foverview)



Search Ctrl K

Use cases

[Overview](https://docs.claude.com/docs/en/about-claude/use-case-guides/overview)[Ticket routing](https://docs.claude.com/docs/en/about-claude/use-case-guides/ticket-routing)[Customer support agent](https://docs.claude.com/docs/en/about-claude/use-case-guides/customer-support-chat)[Content moderation](https://docs.claude.com/docs/en/about-claude/use-case-guides/content-moderation)[Legal summarization](https://docs.claude.com/docs/en/about-claude/use-case-guides/legal-summarization)[Commerce agent](https://docs.claude.com/docs/en/about-claude/use-case-guides/commerce-agents)

Prompt engineering

[Overview](https://docs.claude.com/docs/en/build-with-claude/prompt-engineering/overview)[Prompting best practices](https://docs.claude.com/docs/en/build-with-claude/prompt-engineering/claude-prompting-best-practices)[Prompting Claude Fable 5.1](https://docs.claude.com/docs/en/build-with-claude/prompt-engineering/prompting-claude-fable-5-1)[Prompting Claude Fable 5](https://docs.claude.com/docs/en/build-with-claude/prompt-engineering/prompting-claude-fable-5)[Prompting Claude Opus 5.5](https://docs.claude.com/docs/en/build-with-claude/prompt-engineering/prompting-claude-opus-5-5)[Prompting Claude Opus 5](https://docs.claude.com/docs/en/build-with-claude/prompt-engineering/prompting-claude-opus-5)[Prompting Claude Opus 4.8](https://docs.claude.com/docs/en/build-with-claude/prompt-engineering/prompting-claude-opus-4-8)[Prompting Claude Sonnet 5.5](https://docs.claude.com/docs/en/build-with-claude/prompt-engineering/prompting-claude-sonnet-5-5)[Prompting Claude Sonnet 5](https://docs.claude.com/docs/en/build-with-claude/prompt-engineering/prompting-claude-sonnet-5)

Test and evaluate

[Define success and build evaluations](https://docs.claude.com/docs/en/test-and-evaluate/develop-tests)[Reducing latency](https://docs.claude.com/docs/en/test-and-evaluate/strengthen-guardrails/reduce-latency)

Strengthen guardrails

[Reduce hallucinations](https://docs.claude.com/docs/en/test-and-evaluate/strengthen-guardrails/reduce-hallucinations)[Increase output consistency](https://docs.claude.com/docs/en/test-and-evaluate/strengthen-guardrails/increase-consistency)[Mitigate jailbreaks](https://docs.claude.com/docs/en/test-and-evaluate/strengthen-guardrails/mitigate-jailbreaks)[Reduce prompt leak](https://docs.claude.com/docs/en/test-and-evaluate/strengthen-guardrails/reduce-prompt-leak)

Reference

[Glossary](https://docs.claude.com/docs/en/about-claude/glossary)[Additional resources](https://docs.claude.com/docs/en/about-claude/additional-resources)

[Console](https://docs.claude.com/)

[Best practices](https://docs.claude.com/docs/en/about-claude/use-case-guides/overview)Prompt engineering

# Prompt engineering overview

Copy page



Learn when prompt engineering is the right solution, and find Claude prompting techniques and interactive tutorials.

Copy page



## Before prompt engineering

This guide assumes that you have:

1.   A clear definition of the success criteria for your use case
2.   Some ways to empirically test against those criteria
3.   A first draft prompt you want to improve

If not, spend time establishing that first. Check out [Define success criteria and build evaluations](https://docs.claude.com/docs/en/test-and-evaluate/develop-tests) for tips and guidance.



[Prompt generator notebook](https://colab.research.google.com/github/anthropics/claude-cookbooks/blob/main/misc/metaprompt.ipynb)

Don't have a first draft prompt? Generate one with the metaprompt recipe from the Claude Cookbook.



[Prompting best practices](https://docs.claude.com/docs/en/build-with-claude/prompt-engineering/claude-prompting-best-practices)

For model-specific tuning guidance for Claude's latest models, start here.

* * *

## When to prompt engineer

This guide focuses on success criteria that are controllable through prompt engineering. Not every success criteria or failing eval is best solved by prompt engineering. For example, you can sometimes improve latency and cost more easily by selecting a different model.

* * *

## How to prompt engineer

All prompting techniques (from clarity and examples to XML structuring, role prompting, thinking, and prompt chaining) are covered in [Prompting best practices](https://docs.claude.com/docs/en/build-with-claude/prompt-engineering/claude-prompting-best-practices). That's the living reference; start there.

For general prompt engineering craft beyond Claude-specific techniques, see the blog post on [best practices for prompt engineering](https://claude.com/blog/best-practices-for-prompt-engineering).

* * *

## Prompt engineering tutorial

If you're an interactive learner, you can start with the interactive tutorials instead!



[GitHub prompting tutorial](https://github.com/anthropics/prompt-eng-interactive-tutorial)

An example-filled tutorial on prompt engineering fundamentals. It was written for Claude 3 models, so follow Prompting best practices where the two differ.



[Google Sheets prompting tutorial](https://docs.google.com/spreadsheets/d/19jzLgRruG9kjUQNKtCg1ZjdD6l6weA6qRXG5zLIAhC8)

A lighter-weight version of the prompt engineering tutorial, as an interactive spreadsheet.

Was this page helpful?



*   [Before prompt engineering](https://docs.claude.com/en/docs/build-with-claude/prompt-engineering/overview#before-prompt-engineering)
*   [When to prompt engineer](https://docs.claude.com/en/docs/build-with-claude/prompt-engineering/overview#when-to-prompt-engineer)
*   [How to prompt engineer](https://docs.claude.com/en/docs/build-with-claude/prompt-engineering/overview#how-to-prompt-engineer)
*   [Prompt engineering tutorial](https://docs.claude.com/en/docs/build-with-claude/prompt-engineering/overview#prompt-engineering-tutorial)

[Claude Platform Docs](https://docs.claude.com/docs/en/home)

[](https://x.com/claudeai)[](https://www.threads.com/@claudeai)[](https://www.linkedin.com/showcase/claude)[](https://www.youtube.com/@anthropic-ai)[](https://instagram.com/claudeai)



### Solutions

*   [AI agents](https://claude.com/solutions/agents)
*   [Code modernization](https://claude.com/solutions/code-modernization)
*   [Coding](https://claude.com/solutions/coding)
*   [Customer support](https://claude.com/solutions/customer-support)
*   [Financial services](https://claude.com/solutions/financial-services)
*   [Government](https://claude.com/solutions/government)
*   [Higher education](https://claude.com/solutions/education)
*   [K-12 teachers](https://claude.com/solutions/teachers)
*   [Life sciences](https://claude.com/solutions/life-sciences)

### Partners

*   [Claude on AWS](https://claude.com/partners/amazon-bedrock)
*   [Claude on Google Cloud](https://claude.com/partners/google-cloud-vertex-ai)

### Learn

*   [Blog](https://claude.com/blog)
*   [Courses](https://claude.com/resources/courses)
*   [Use cases](https://claude.com/resources/use-cases)
*   [Connectors](https://claude.com/partners/mcp)
*   [Customer stories](https://claude.com/customers)
*   [Engineering at Anthropic](https://www.anthropic.com/engineering)
*   [Events](https://www.anthropic.com/events)
*   [Powered by Claude](https://claude.com/partners/powered-by-claude)
*   [Service partners](https://claude.com/partners/services)
*   [Startups program](https://claude.com/programs/startups)

### Company

*   [Anthropic](https://www.anthropic.com/company)
*   [Careers](https://www.anthropic.com/careers)
*   [Economic Futures](https://www.anthropic.com/economic-futures)
*   [Research](https://www.anthropic.com/research)
*   [News](https://www.anthropic.com/news)
*   [Responsible Scaling Policy](https://www.anthropic.com/news/announcing-our-updated-responsible-scaling-policy)
*   [Security and compliance](https://trust.anthropic.com/)
*   [Transparency](https://www.anthropic.com/transparency)

### Learn

*   [Blog](https://claude.com/blog)
*   [Courses](https://claude.com/resources/courses)
*   [Use cases](https://claude.com/resources/use-cases)
*   [Connectors](https://claude.com/partners/mcp)
*   [Customer stories](https://claude.com/customers)
*   [Engineering at Anthropic](https://www.anthropic.com/engineering)
*   [Events](https://www.anthropic.com/events)
*   [Powered by Claude](https://claude.com/partners/powered-by-claude)
*   [Service partners](https://claude.com/partners/services)
*   [Startups program](https://claude.com/programs/startups)

### Help and security

*   [Availability](https://www.anthropic.com/supported-countries)
*   [Status](https://status.claude.com/)
*   [Support](https://support.claude.com/)
*   [Discord](https://www.anthropic.com/discord)

### Terms and policies

*   [Privacy policy](https://www.anthropic.com/legal/privacy)
*   [Responsible disclosure policy](https://www.anthropic.com/responsible-disclosure-policy)
*   [Terms of service: Commercial](https://www.anthropic.com/legal/commercial-terms)
*   [Terms of service: Consumer](https://www.anthropic.com/legal/consumer-terms)
*   [Usage policy](https://www.anthropic.com/legal/aup)

Ask Docs

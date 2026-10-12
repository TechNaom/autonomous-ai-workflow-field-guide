# References

Platform documentation and sources consulted, opened on 13 October 2026.

## LinkedIn platform

- [Share on LinkedIn](https://learn.microsoft.com/en-us/linkedin/consumer/integrations/self-serve/share-on-linkedin): posting as a member, the `w_member_social` scope, and per-member daily limits
- [Refresh Tokens with OAuth 2.0](https://learn.microsoft.com/en-us/linkedin/shared/authentication/programmatic-refresh-tokens): 60-day access tokens; refresh tokens only for approved partners
- [LinkedIn API Rate Limiting](https://learn.microsoft.com/en-us/linkedin/shared/api-guide/concepts/rate-limits): daily limits reset at midnight UTC; HTTP 429 when exceeded
- [Prohibited software and extensions](https://www.linkedin.com/help/linkedin/answer/a1341387): bots, scrapers and automation extensions are not permitted
- [Content credentials](https://www.linkedin.com/help/linkedin/answer/a6282984): C2PA labels on images and video
- [How LinkedIn is improving the Feed](https://news.linkedin.com/2026/ImprovingTheFeed), 12 March 2026: favouring genuine insight; reducing repetitive posts, engagement bait and engagement pods

## Analytics

- [LinkedIn enables third-party analytics access with new Member Post API](https://ppc.land/linkedin-enables-third-party-analytics-access-with-new-member-post-api/), PPC Land: the Member Post Analytics API, launched 8 July 2025, available to approved vendors

## Standards and techniques

- [OpenTelemetry GenAI semantic conventions](https://github.com/open-telemetry/semantic-conventions-genai): spans, metrics and attributes for model calls (still evolving)
- [Building effective agents](https://www.anthropic.com/engineering/building-effective-agents), Anthropic: the distinction between workflows and agents used in this guide

# ai appointment setter pricing: how CloseBot's per-message model works, what 500 replies actually cost, and which plan fits your setup

Most people searching this have the same number in the back of their head: a human setter costs around $2,000 a month, so what does the AI version cost, and is the swap real? The honest answer is that "AI appointment setter pricing" isn't one number. It's three or four billing models stacked on top of each other, and the model you pick matters more than the sticker price.

Some tools charge per minute of voice. Some charge per message. Some charge a flat platform fee plus usage. A few bury a second product underneath, like a CRM you have to buy before the setter does anything.

CloseBot sits in the platform-fee-plus-usage camp, and its pricing page is unusually specific about where the money goes. Here's the actual math, including the parts that don't appear on the pricing page.

## The billing models you'll run into

Before comparing dollar figures, it helps to know what you're comparing.

**Per message (or per segment).** You pay a monthly platform fee plus a small charge for each AI reply. CloseBot works this way, so does GoHighLevel's native Conversation AI at $0.02 per message.

**Per minute.** Typical of voice agents. Retell AI publishes $0.07 to $0.31 per minute with no platform fee, plus 60 free minutes to start.

**Flat monthly, done-for-you.** Someone builds and runs the agent. Setter AI lists $497/month on its entry tier, Call Setter AI starts from $497/month plus a build, and 11x lists $2,417/month for its chat agent and $5,333/month for voice, both billed annually.

**Per call or per agent.** AIRA runs $24.95 to $299 per month by call volume; Goodcall charges per agent from $79 to $249.

None of these is automatically cheaper. A per-minute tool with low call volume beats a per-message tool with high chat volume, and vice versa. What kills budgets is picking a model that doesn't match how your leads actually contact you.

## CloseBot's full plan lineup, as currently listed

CloseBot's pricing page shows three plan names with one split inside them: Free, Core (available as a business plan or an agency plan), and Growth, which is custom-quoted. Here's the whole board.

| Plan | Price | Billing | What you actually get | Buy |
| --- | --- | --- | --- | --- |
| Free | $0 | Always free | 100 messages/month, 1 agent, 1 user seat, 1 MB upload storage, unlimited account connections | [Start on the free plan](https://app.closebot.com/a?fpr=li87) |
| Core (Business) | From $64/mo monthly; $53/mo effective, billed as $640/yr annually | Monthly or annual | 500 messages/month included, 15+ templates (50+ extra templates on annual plans), human support, extra users at $5 each, add-on storage and agents | [See the business plans](https://app.closebot.com/a?fpr=li87) |
| Core (Agency) | $397/mo monthly; roughly $331/mo equivalent billed annually | Monthly or annual | Unlimited agents and sources, white-label client portal, rebill all costs at $0.012/message, extra seats at $5 | [Compare the agency plan](https://app.closebot.com/a?fpr=li87) |
| Growth | Custom | Custom | HIPAA compliance, quarterly audits, 99.99% priority uptime, priority support, 50+ templates, SLA terms | [Request Growth pricing](https://app.closebot.com/a?fpr=li87) |

A few notes on that table, because the details are where the real cost lives.

The $53/month annual figure isn't a discount code. $640 divided by twelve is $53.33, and $640 is ten months at the $64 monthly rate. Pay annually and you're covering ten months of usage instead of twelve. The trade-off is that CloseBot states plainly there are no refunds, so annual billing means committing before you've tested much.

The business plan's $64 entry price includes 500 messages. The pricing page has a slider running from 100 monthly AI replies up to 100,000+, and the business plan price moves with it. The Free tier sits at the 100-message mark.

Growth isn't a bigger version of Core. It's aimed at teams that need paperwork: HIPAA compliance, quarterly audits, a 99.99% priority uptime commitment, SLA terms, and priority support. If your compliance officer has to sign off, this is the tier that conversation happens on.

## Where CloseBot's usage costs actually land

Message billing has a quirk worth understanding before you budget.

One message equals one segment. An agent that replies six times during a conversation has spent six of your monthly allowance, not one. And if you switch on the Agent Node's "unlimited potential" setting, which unlocks larger instruction sizes and more tools, billing shifts to token costs, meaning a single message can consume several segments instead.

That's the difference between "500 messages is plenty" and "why did 500 messages disappear in a week."

For the Free plan, the ceiling is 100 messages. Go past it and you pay $0.08 per message as you go, which the docs suggest is a signal to move to a paid tier rather than a long-term arrangement.

For business plans, the included allowance is 500 messages, and you can raise the ceiling monthly to get better bulk rates. Cross the ceiling and you pay a 2x overage rate drawn from your wallet, which you can turn on as overage protection.

For agency plans, CloseBot bills a flat $0.012 per message, deductable from your wallet and rebillable to clients at whatever markup you set. Customer seats rebill at $5 each, and knowledge-base storage rebills at $0.006 per MB per day. Agencies connect their own Stripe account, and the wallet top-ups clients pay go straight to the agency.

👉 [Check the current plan breakdown before you commit](https://app.closebot.com/a?fpr=li87)

## The costs that don't appear on the pricing page

This is the part most pricing roundups skip, and it's where the comparison either makes sense or falls apart.

**The CRM underneath.** CloseBot integrates natively with HighLevel, HubSpot, LeadConnector, and custom CRMs, taking over the text channels already running inside them. It also works standalone. But if your leads live in GoHighLevel, you're paying for GoHighLevel: $97/month for Starter, $297/month for Unlimited, $497/month for Agency Pro as listed on HighLevel's pricing page. A business running 500 CloseBot messages on the entry tier is realistically at $64 plus $97, before any WhatsApp or SMS fees.

**Seats and storage.** The base plan includes one user. Additional users are $5 each per month on both business and agency plans. Storage add-ons on business plans run $0.10 to $3.00 per MB per month depending on volume; agencies pay $0.006 per MB per day and can rebill it.

**No bring-your-own API key.** CloseBot doesn't allow plugging in your own OpenAI or Anthropic key. The company frames this as a security and compliance decision. Practical effect: your model spend is baked into the plan, so you lose the option of trimming token costs by switching providers on your own terms.

**No refunds, but a real trial.** Any paid plan gets a 7-day trial before billing starts. After that, no refunds. Plans run month to month with no contract, so upgrading, downgrading, or cancelling is straightforward.

## How CloseBot's pricing compares, side by side

| Tool | Published pricing | Model | Notes |
| --- | --- | --- | --- |
| CloseBot Free | $0 | Platform | 100 messages, 1 agent, 1 seat |
| CloseBot Core (Business) | From $64/mo, or $53/mo annual | Platform + included messages | 500 messages included, then 2x overage |
| CloseBot Core (Agency) | $397/mo ($331/mo annual equiv.) | Platform + $0.012/msg | Rebillable to clients, white label |
| Retell AI | $0.07–$0.31/min | Usage, voice | 60 free minutes, 20 concurrent calls |
| Setter AI | $497/mo entry as listed | Flat, done-for-you | Higher tiers listed at $2,297 and $3,497 |
| Appointwise | $97–$297/mo | Flat | Markets itself against $2,000/mo human setters |
| 11x (Julian) | $2,417/mo chat, $5,333/mo voice | Enterprise, annual | Aimed at B2B pipeline teams |
| GoHighLevel Conversation AI | $0.02/message | Usage | Sits inside a CRM you're already paying for |

Read that table by channel, not by price. If your leads call you, a per-minute voice tool is the right shape and per-message pricing is irrelevant. If your leads text, per-minute pricing wastes money and a per-message tool is the better fit.

CloseBot itself publishes a cost comparison arguing that at scale, per-message pricing beats HighLevel's $97 per sub-account unlimited AI Employee plan. That's a vendor argument, and it assumes you're running real volume. At four sub-accounts, HighLevel's unlimited option comes out around $388/month against CloseBot's $397 base plus usage.

## Which plan fits which situation

**You want to see how it behaves before spending anything.** Free plan. 100 messages, one agent, one seat, no credit card. Enough to build an agent and watch it handle a real conversation. Not enough to run a business on.

**You're a business qualifying your own leads.** Core business. The $64 entry tier includes 500 messages and no per-message cost until you exceed the ceiling, which makes budgeting predictable in a way metered pricing usually isn't. Move the slider up only when your lead volume actually justifies it.

**You're an agency selling AI setting as a service.** Core agency. The whole reason to pay $397 instead of $64 is the rebilling stack: $0.012 per message, $5 seats, and storage you can mark up, all flowing through your own Stripe account. If you're not reselling, you're paying agency pricing for features you'll never touch.

**You need compliance paperwork or uptime guarantees.** Growth. HIPAA, quarterly audits, and SLA terms are the difference between this tier and Core, and there's no published price.

One thing worth saying plainly: no AI setter closes deals. CloseBot books appointments and handles follow-up. The close still happens on the call with a human, which means the number that actually matters isn't the subscription, it's cost per booked appointment. That's a figure you can only get from running the free plan or the 7-day trial against your own lead flow.

👉 [Run your own numbers on the free plan](https://app.closebot.com/a?fpr=li87)

## FAQ

**Is there a free trial?**
Two things, technically. There's a free-forever plan capped at 100 messages a month, and a 7-day trial of any paid plan before billing starts. CloseBot states there are no refunds after the trial, which is why the trial is where you do your testing.

**What happens if I go over my message allowance?**
On the free plan, $0.08 per message pay-as-you-go. On business plans, a 2x overage rate drawn from your wallet, with wallet-based overage protection available. On agency plans, the flat $0.012 per message rate continues, and you rebill it.

**Do I need a CRM to use it?**
CloseBot is built to run inside one: HighLevel, HubSpot, LeadConnector, or a custom CRM, and it takes over whatever text channels are connected there. It also advertises standalone compatibility, meaning it works without a CRM. If your leads arrive as Instagram or WhatsApp DMs and you don't run a CRM, your CRM's inbox is what CloseBot answers, not the platform itself.

**Can I use my own OpenAI or Anthropic API key to cut costs?**
No. CloseBot disallows bring-your-own-key, citing security. You can choose which provider generates responses per persona, but the spend stays inside the plan.

**How do agencies make money on it?**
By marking up usage. CloseBot charges the agency $0.012 per message, and the agency sets its own rate for clients. Seats and storage markups work the same way, and payments flow through the agency's connected Stripe account. CloseBot's own page notes some agencies charge around $100 per client per month while others bill $10,000+ from a single client, so the margin is whatever the agency can justify.

**Is annual billing worth it?**
For Core, annual billing works out to $53/month billed as $640 per year, which is ten months of the monthly rate. You save the equivalent of two months, but you pay upfront, and refunds aren't offered. If you've already run the trial and know the fit is right, the math is straightforward. If not, stay monthly until it is.

## The short version

CloseBot's entry price is $0 for 100 messages and $64 a month for 500, with annual billing dropping that to $53 a month. The agency plan at $397 a month is a different product aimed at resellers, and the entire value there is rebilling. Budget for the CRM underneath if you use one, remember that seats and storage are separate line items, and don't expect to bring your own API key to trim the bill.

The right way to judge any of this is cost per booked appointment on your own leads, and the free plan is the cheapest way to find out what that number looks like.

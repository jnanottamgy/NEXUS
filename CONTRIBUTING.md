# Keeping this repository current

[← NEXUS home](README.md)

This guide is for the **NEXUS core team**. Everything here is plain Markdown, so you can do all of it from the GitHub website without installing anything. The [IT department](departments/it.md) maintains the repo and is happy to help.

**Everyone else:** please use the [issue forms](https://github.com/jnanottamgy/NEXUS/issues/new/choose) to propose events, suggest ideas or report something wrong.

## Editing on the GitHub website

- **Edit a file:** open it, click the pencil icon, make your change, and click **Commit changes**.
- **Add a file:** go to the folder, click **Add file → Create new file**, type the file name, write, and commit.
- **Not sure?** Choose **Create a new branch and start a pull request** when committing, and someone from IT will review it.

## Posting an update

Announcements, event news, recaps, news digests and explainers all go in [`updates/`](updates/README.md).

1. Copy [`updates/TEMPLATE.md`](updates/TEMPLATE.md) into a new file named `YYYY-MM-DD-short-title.md`, for example `2026-11-02-budget-session-recap.md`.
2. Fill it in.
3. Add a row at the **top** of the table in [`updates/README.md`](updates/README.md).
4. Add the same row at the top of **Latest updates** in the [home page](README.md#latest-updates). Keep only the **five** most recent there.
5. If it's an event, update [`events/README.md`](events/README.md) too.

## Roster changes

When someone joins, leaves or changes role, update **all** of these in the same commit so nothing goes out of date:

- [ ] The wing or department table on the [home page](README.md)
- [ ] The wing or department's own page in [`wings/`](wings/) or [`departments/`](departments/)
- [ ] [JOIN.md](JOIN.md): remove filled positions, add new openings
- [ ] The role list in [`.github/ISSUE_TEMPLATE/join-open-role.yml`](.github/ISSUE_TEMPLATE/join-open-role.yml)
- [ ] An update in [`updates/`](updates/README.md) welcoming the new member (optional, but nice)

## Content rules

These apply to this repo, our sessions and our social media.

- **Educational only.** No buy/sell recommendations, stock or crypto "tips", trading signals or target prices.
- **No paid promotion** of investment products, trading platforms, tokens, referral links or paid courses through club channels.
- **Cite your sources.** Link to the RBI, SEBI, the Budget documents, company filings or reputable news, not screenshots of someone's post.
- **Add the disclaimer.** Anything about investing, trading or crypto should say it's educational and not financial advice.
- **Protect privacy.** Never post phone numbers, personal email addresses, USNs or addresses of members or applicants.
- **Dates** are written as `07 Oct 2026` in tables and text, and as `2026-10-07` in file names.

## Handover

At the end of each tenure, the outgoing team updates the roster, archives the year's events under [past events](events/README.md#past-events), and transfers repo access to the incoming President and IT department.

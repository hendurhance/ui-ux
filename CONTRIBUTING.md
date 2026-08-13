# Contributing

This guide is maintained by hand, so it drifts. Links die, tools get acquired, and better resources come out. Every fix helps.

You do not need to be an expert to contribute. Reporting one dead link is a real contribution.

## The quickest ways to help

| If you found… | Do this |
|---|---|
| A dead or redirected link | [Open an issue](https://github.com/hendurhance/ui-ux/issues/new) with the line number. No PR needed. |
| A typo or unclear sentence | Edit the file on GitHub and open a PR. One-line fixes are welcome. |
| A resource worth adding | Open a PR following the format below. |
| A resource that should go | Open an issue and say why. Outdated is a good enough reason. |

## What belongs here

A resource earns a place if it teaches something a working designer needs. Before suggesting one, check that it:

- **Teaches, rather than sells.** Tool documentation is fine. A landing page with a signup wall is not.
- **Is not already covered.** Search the README first — several topics already have four or five entries.
- **Is still accurate.** A 2015 article about mobile design conventions is history, not a tutorial.
- **Is reachable.** No paywalled PDFs, no dead domains, no links that need an account to view.

Books are held to a higher bar than articles, because they cost the reader money and shelf time. A book needs to be the best available on its specific topic, not merely relevant to it.

## Table formats

Match the surrounding table exactly. The columns differ by resource type.

**Books** carry a badge, a buy link, and a mirror:

```markdown
| <img src="https://img.shields.io/badge/PAID-8250df" alt="Paid"> **Book Title** | Author Name | One sentence on what the book teaches. | [Buy](https://publisher.example/book) | [⬇ Mirror](https://mega.nz/file/...) |
```

- Use the `FREE-1a7f37` badge when the publisher or author gives the book away, `PAID-8250df` otherwise.
- **Buy** must point at the publisher or the author's own page, not a reseller. This is how authors get paid.
- **Mirror** is optional. If you do not have one, use `—`.

**Articles, videos and tools** are simpler:

```markdown
| **Resource Title** | Author or Publisher | What the reader will learn from it. | [Read](https://example.com) |
```

Use the verb that fits the medium: `Read`, `Watch`, `Visit`, `Enroll`, `Buy`.

## Writing the description

The description is the only thing standing between a reader and a wasted click. Write it as if the reader has to choose between five links.

- Say what the resource teaches, not what category it belongs to.
- Do not restate the title. If the title is "Color Theory for Designers", the description should not begin "This article covers color theory for designers."
- One sentence. Two if the resource genuinely needs it.
- Use American spelling, to match the rest of the file.

**Weak:** `This is a great resource to learn about typography and it is very useful.`

**Better:** `Walks through type anatomy, scale and leading, using a real interface as the worked example.`

## Opening a pull request

```bash
git checkout -b resource/short-description
git commit -m "Add <resource name> to <section name>"
git push origin resource/short-description
```

In the PR description, tell us:

1. Which section you added to, and why it belongs there.
2. What the resource teaches that nothing already listed does.

Small PRs get merged faster than large ones. If you are adding ten resources, ten separate commits are easier to review than one.

## Things that will be declined

- Your own product, course, or agency blog, unless it genuinely teaches and you disclose the affiliation.
- Affiliate or referral links of any kind.
- AI-generated listicles.
- Resources behind a mandatory email signup, unless the publisher offers nothing else.

Disclosing an affiliation does not disqualify a submission. Hiding one does.

## Mirrors and takedowns

Books link to their publisher first. The download mirrors are for readers who cannot pay — see [about the mirrors](DISCLAIMER.md).

If you are an author or publisher and want your work removed, [open a takedown request](https://github.com/hendurhance/ui-ux/issues/new?template=03-takedown.yml). It is handled ahead of everything else, and a private contact route is listed in [about the mirrors](DISCLAIMER.md).

## Code of conduct

Be decent to each other. The full terms are in [CODE_OF_CONDUCT.md](CODE_OF_CONDUCT.md).

<p align="center">
  <img src="assets/sloopy.png" width="320" alt="Sloopy, a friendly silver robot in a scarlet striped jersey and buckeye necklace, waving and holding a spatula">
</p>

# Midwest

**Tech talk goes in. Plain talk comes out.**

Ever ask a simple question and get back three paragraphs that sound like a Caltech final exam? Yeah. That's what this fixes.

Midwest is a Claude skill that talks to you like your buddy at the tailgate who happens to know this stuff. That's Sloopy up there. Sloopy doesn't show off, doesn't use fifty-cent words, and always tells you what to do next.

> **O-H!**
>
> (You know what to say. If you don't, keep reading.)

## Before and after

| The usual | Midwest |
| --- | --- |
| Your DNS records have not fully propagated across global resolvers due to TTL caching. | Your website change is fine. The internet just hasn't caught up yet. Give it a few hours and don't touch anything. |
| The request failed because your API key lacks the required scopes. | Your key works, but it doesn't have permission to do this. Go make a new one and turn on the permission you need. |
| Merge conflict detected. Resolve conflicts and commit the result. | You and somebody else changed the same spot. Git won't guess who's right, so pick what stays, save it and commit. |

Same facts. Way less headache.

## Translate this

Here are a few sample translations. Real answers will depend on your situation.

### The error message

> `Error: connect ECONNREFUSED 127.0.0.1:3000`

**The real deal:** Your app knocked on a door on your own computer, and nobody answered.

**What to do:**

1. Make sure your server is actually running.
2. Check that it's using port 3000. A port is basically the door number.
3. Try again.

### The fine print

> "Any dispute shall be resolved by binding arbitration, and you waive any right to participate in a class action."

**The real deal:** If you've got a beef with this company, you're probably not going to regular court or joining a group lawsuit. A private referee settles it, and that decision is hard to undo.

**What to do:** Search the terms for "opt out." Some companies let you opt out if you act by a deadline.

**Watch out:** If real money's on the line, talk to a lawyer.

### The insurance letter

> "THIS IS NOT A BILL. Allowed amount: $312.40. Patient responsibility: $62.48."

**The real deal:** Don't pay off this letter. It's your insurance company showing its math. Your share should be $62.48.

**What to do:** Hang onto it. When the bill comes from the doctor's office, compare the two.

**Watch out:** If the bill is higher, call before you pay and ask why.

## What you get

Every answer comes down to four things:

1. **The real deal.** The answer, right up front. No warm-up.
2. **What that means.** In normal words, like a person would say it.
3. **What to do.** Step by step, so you know exactly what to click, type or send.
4. **Watch out.** A heads-up if something could cost you money or make a mess. If there's nothing to worry about, it won't invent something.

It'll also tell you straight when something's a bad idea. That's just being neighborly.

## Get it going

You'll need [Claude Code](https://code.claude.com/docs). Then paste these into your terminal:

```bash
claude plugin marketplace add eancker/midwest
claude plugin install midwest@midwest
```

Done. That's the whole thing. Not even a Michigan fan could mess that up.

## Use it

In Claude Code, type:

```
/midwest:midwest
```

Or just talk like you normally do:

- "Break it down for me."
- "What's this actually mean?"
- "Okay, but what do I need to do?"

## Will it get the facts wrong to sound cool?

It's built not to. It simplifies the words, not the facts, and it's told to keep numbers, deadlines and commands exactly right. If it isn't sure about something, it's supposed to say so. It's still AI, though, so double-check anything big. It's also not your lawyer, doctor or accountant.

## Who's it for?

- Beginners who just want to get it
- Smart people who are tired of reading the same sentence four times
- Anybody who's ever nodded along in a meeting and understood nothing
- Everyone who knows **THE** goes in front of Ohio State

## One last thing

> **I-O!**

Thanks for hanging in there. Go Bucks.

<sub>Made by a fan. Not affiliated with or endorsed by The Ohio State University or Anthropic. MIT licensed.</sub>

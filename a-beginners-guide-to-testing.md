# A beginner's guide to testing

Many testers have found struggling in getting started and continuing their activity with the MoonlightBot test program. This guide aims to extensively clear any doubt out.

## Preliminary

You don't need any special previous experience to contribute to a test. We aim to provide an inclusive experience to keen users.

If you have already used MoonlightBot beta, you may be more familiar with changelogs and using new features.

## An overview to the test zone

Once you acquired the **MoonlightBot testers** role, you have officially become a tester. Congratulations. Now, you can see some exclusive important channels. Let's view them in detail:

![List of test channels](<.gitbook/assets/immagine (5).png>)

* **#test-info** contains some important information, a link to invite MoonlightBot test to your server, and changelogs for new test updates
* **#test-chat** is the main point of communication for anything related to testing. This can range from questions to making observations, sharing details with other testers, etc. Make sure to jump in once in a while!
* **#test-feedback** is for pushing for change as you wish. Here you can voice your feedback to be brought up to developers. Don't be afraid of saying your own!
* **#test-bug**-**reports **allows you to submit bugs found during testing. See \[submitting bugs] for more details

## Beginning the test

The first thing you have to do to get started is inviting **MoonlightBot test** to your server. This special instance of MoonlightBot is the one with the updated features. It operates like the normal MoonlightBot, with exceptions made in some updates. You can find the invite link in **#test-info**.

{% hint style="info" %}
It is advised that you test in a small dedicated server instead of adding MoonlightBot test to your "populated" server. Its new features are highly unsuitable for the public.
{% endhint %}

MoonlightBot test's prefix is `p:`. Mentioning it works as well.

You'll need to learn a bit about the new features, so let's move onto changelogs.

## Interpreting changelogs

Changelogs are calls to actions that announce that a new bot version has been released, and describes all changes made. Let's analyze one:

![Orient yourself with the numbers on the left and the highlighted parts](<.gitbook/assets/immagine (6).png>)

1. **Version number: **the version the bot has been updated to. This number may be followed by a `patch-X` to indicate very minor changes during test
2. **New command: **indicates that one or more new commands have been added. Try them out! Command names and aliases are written inside `code blocks` so you can't mistake them
3. **Explanations:** a bit more background on the update contents. Read it all to acquire knowledge on how the new features work
4. **Log names:** they're eventually added and documented along with their category. You should set them and watch what happens. For more information on how to configure logs, see [this page](https://moonlightbot.gitbook.io/docs/admin-commands/config/configuring-channels)
5. **Final notes:** they may be changes only developers can see which are likely code quality fixes. Keep them in mind in case something that worked previously breaks after an update

Not all changelogs are equal or contain so many information. Usually the big deal is in the first changelog for a test, then the subsequent others are small improvements or bug fixes.

{% hint style="success" %}
It is advised that you keep notifications enabled for **#test-info**, since changelogs are sent there. Most of them are accompanied by a tester role ping, but should not this happen, keep watching the channel
{% endhint %}

You should respond to a changelog by testing out all changes. Not often it happens that fixing a bug creates some more afterwards. In the next session, you'll see how to prepare yourself to discuss changes.

## Debating and sharing progress

Whenever you do some testing activity, you should report your progress to other testers. You can do that in **#test-chat**.

It is always encouraged to ask questions and say opinions about the new features. It is very important to make the bot user-friendly before launching new features. Normal users would be disappointed otherwise.

You can post screenshots, videos, concept sketches... Anything costructive is appreciated!

## How to report a bug

It is reasonable that while trying to use a feature that needs testing, you may find a bug. Those can be reported for the developers to quickly fix them.

The following is considered a valid bug:

* Any "Something went really wrong while executing the command..." message
  * Remember to put the error ID in the message content and not only in a screenshot. It will make easier to copy and paste
  * If you are on mobile, you may find easier to copy the ID from the message containing the command (the one you send), as the two are identical
* Typos (yes, even if very minor, they should be corrected)
* Any of the following text appearing in command responses: `null`, `undefined`, `NaN`, `[object Object]`, or any other weird text. They correspond to programmer oversights
* Inconsistent behavior, such as non-existent options not showing, missing help/argument/usage descriptions, negative values where they shouldn't be (like in a quantity, it doesn't make sense to set -10 infractions)
* Bot spamming you or acting weird (Discord outages/downtime unless caused by your input are NOT bugs)

Bug reports should be sent in **#test-bug-reports**. There's a pinned message containing the format to follow to submit your bug, so please follow it.

{% hint style="info" %}
Add as much information as you can. You may be contacted by Staff/developers for more details on what happened.
{% endhint %}

### Finding the bot version

The bot version is found in the `p:stats` command, in the footer. Example:

![Highlighted in yellow is the current bot version](<.gitbook/assets/immagine (9).png>)

{% hint style="warning" %}
It is frequent that in a test the patch version updates. Please include that as well as it's important information.
{% endhint %}

## Tips to find bugs

Here's a non-exaustive list to find bugs

* **Breaking the limit:** can you try to input values that go over a limit? What about under? What abouts the extremes of an interval itself?
* **Wrong is right:** what happens if you do things wrong on purpose just for the sake of doing it? The bot should always be resilient and tell you what you did wrong instead of accepting what you throw at it
* **Environment changes:** mess with permissions, both Discord's and the bot's (levels)
* **Touch someone else's stuff:** some things may need being locked to a specific user/server/channel. You should really try to mess with data that doesn't belong to you
* **Just try doing something, really:** most bugs are left uncaught because testers don't test some components they should

A bug can appear in any moment at any time. Don't be afraid of breaking things, you are in a controlled environment and can't actualy hurt anybody and anything.

## Submitting good feedback

Improving features during the development process is the quickest and easiest way to finish with a good result that appeals a vast group of users. Even if it's the littlest annoyance ever, you should not be afraid to say your opinion for matters like this.

You can submit your feedback in **#test-feedback**. Like for bug reports, there's a format to follow pinned in the channel.

As for this section, there are no specific rules to follow. Your feedback is best understood if:

* You explain what the current problem at the beginning
* Present one or more solutions you would find feasible
* Include screenshots and sketches of your solutions

{% hint style="info" %}
Try to discuss other testers' feedback with your own ideas! If someone comments your feedback, please keep your comments civil.
{% endhint %}

## Finishing FAQs

### Something unexpected happened during the test, and I cannot be active anymore. What should I do?

Please contact a Staff member about this. It is not nice to disappear without saying anything in a program of trust like this.

### This guide does not help me, can I get further assistance?

Of course! The Moonlight Labs Staff team is always listening to your concerns and ready to help!

### Are my questions stupid?

No.

### Am I asking too many questions?

No.

### Is there anything anything really forbidden?

Please don't exploit the test bot (or any other instance of MoonlightBot for the matter) maliciously.

The most forbidden thing is doing nothing.

{% hint style="danger" %}
It is against the server rules and MoonlightBot acceptable use policy to sign up for a test, then do nothing without explaining further, ignore Staff reminders and the like. Be courteous to your peers!
{% endhint %}

### What do I get for completing a test?

If you did not try to do anything, you will receive a punishment.

For the rest, this testing volunteer program is to offer you an opportunity to hone your teamwork and logic skills. Make good use of them!

Sometimes you may receive some material rewards like roles, premium free trials, your name being public on related changelogs (with your consent). If your performance was good, you may be reinvited to other tests to build up even more experience, usually after your first test.

### Can I get credited for this, as in, mention in other places that I completed a test?

Absolutely! Direct the people in need to talk to Staff about experience and we'll be happy to certify your participation.

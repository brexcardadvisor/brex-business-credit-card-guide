# Brex Login and Dashboard Mastery: A Step-by-Step Walkthrough of Managing Your Brex Account Day to Day

Most guides to corporate cards stop at the application. This one starts where your working day actually begins: at the [brex](https://brexcardadvisor.com) sign-in screen. Once a company is approved, the dashboard becomes the place where cards are issued, limits are tuned, receipts are chased, rewards are redeemed and month-end close gets done. If you cannot find your way around that dashboard, you are only using a fraction of what the platform offers.

This walkthrough takes you through the complete day-to-day experience, step by step. You will learn how to complete the [brex login](https://brexcardadvisor.com/brex-login) safely, how to set up two-factor authentication and passkeys, what each part of the dashboard is for, and how to manage cards, limits, rewards, fees and team members without calling support every five minutes. Along the way we will look at the [brex card](https://brexcardadvisor.com/brex-card) itself, the business account that sits behind it, and the small habits that separate a tidy finance operation from a messy one.

A quick note on who is writing: Brex Card Advisor is an independent guide, not affiliated with Brex Inc. or Capital One. We document the [brex company](https://brexcardadvisor.com) platform as experienced users, and everything here is written to help you operate your account with confidence. Typing [brex com](https://brexcardadvisor.com) into a browser is how most people first arrive at the platform — bookmarking the right pages, as you will see below, is how you stay safe once you are a customer.

![The Brex login screen on a laptop, ready for a secure sign-in](img-01.jpg)

## Why the Dashboard Matters More Than the Card

A corporate card on its own is just a piece of plastic or a row of digits. The value of a modern spend platform is the control layer behind the card: real-time visibility of every transaction, per-employee limits, automatic receipt matching and accounting integrations that close the books faster. Every one of those features lives in the dashboard, not on the card.

That is why [brex business](https://brexcardadvisor.com/brex-business-account) customers tend to fall into two camps. The first camp signs in once a month, downloads a statement and wonders why expenses still feel chaotic. The second camp builds small daily and weekly routines — checking the transaction feed, nudging missing receipts, reviewing limit requests — and finds that the finance function nearly runs itself. This guide is written for the second camp.

## Step by Step: The Brex Login Process

Let us start at the front door. The sign-in flow is short, but each step exists for a reason, and knowing what to expect makes troubleshooting far easier later.

### Step 1: Go to the Official Sign-In Page

Open your browser and navigate to the official Brex website, then choose the sign-in option. Brex's legitimate sign-in environments run on its own domains — the web dashboard is reached through dashboard.brex.com and the authentication flow through accounts.brex.com. Brex itself recommends bookmarking the real site rather than searching for it every day, because lookalike pages designed to harvest credentials are a genuine risk for financial accounts. A padlock icon alone proves nothing; fraudulent sites can have valid HTTPS certificates too. The domain is what matters.

### Step 2: Enter Your Account Email

Type the email address associated with your Brex account. This must be the exact email your administrator used when inviting you, or the one you applied with. If your company uses Google or Microsoft sign-in, you may be offered the option to authenticate with that company account instead — the email on that account still has to match the email on your Brex profile.

### Step 3: Enter Your Password

Enter your password. It should be unique to Brex — reusing a password from another service means a breach elsewhere can hand attackers a working key to your finance platform. If you have forgotten it, use the official password-reset flow: Brex emails a reset link to the account email, and only to that email.

### Step 4: Complete Multi-Factor Authentication

Every password-based Brex account is required to use MFA. Depending on your setup, you will approve the sign-in with an authenticator app code or a six-digit SMS code. Brex recommends an authenticator app over SMS because app codes do not depend on mobile signal and are harder to intercept. Enter the code promptly; codes are time-sensitive.

### Step 5: Verify a New Device or Browser (When Asked)

Signing in from a new browser or device can trigger an extra device-verification step. Brex sends an email — it may come from verifications@brex.com or noreply@brex.com — containing the action to authorise that browser. If several verification emails pile up, always use the newest one. Afterwards you will usually be asked whether to trust the device: trusting keeps that browser verified for an extended period (around a year), while "allow once" is the safer choice on any shared or public machine.

### Step 6: Land on the Dashboard Home

After authentication you arrive at the dashboard home, where your view depends on your role. Administrators see company-wide spend, cards, accounts and settings; employees see their own cards, limits and expenses. Same login, different lens — permissions shape everything you see from here on.

![A step-by-step view of entering credentials and completing two-factor authentication](img-02.jpg)

## Step by Step: Setting Up Stronger Sign-In Security

The login is also where your account security is won or lost. Spend ten minutes on these settings once, and every future sign-in gets both safer and faster.

### Step 1: Confirm Your MFA Method

In your personal security settings, check which second factor is registered. If it is SMS and you have the option, add an authenticator app — common authenticator apps and password managers with built-in code generation are supported. Confirm you can generate a code before you rely on it.

### Step 2: Save Your Recovery Codes

When an authenticator method is configured, Brex provides recovery codes. Each code works once. Save them somewhere secure and separate from your phone — a company password manager vault is ideal. If you lose your phone without recovery codes, an administrator can send you a time-limited recovery code to your account email, but that depends on an admin being available when you are locked out at an airport.

### Step 3: Create a Passkey

Eligible users can create a passkey from the security and privacy area of personal settings. A passkey lets you sign in with the same gesture that unlocks your device — Face ID, Touch ID, a fingerprint, a device PIN or a hardware security key. For eligible users it can replace both the password and the MFA step, and because a passkey cannot be typed into a fake website, it is strongly resistant to phishing. Allow pop-ups for the dashboard during setup, since the creation flow may open one.

### Step 4: Know Whether Your Company Uses SSO

Larger organisations may route sign-in through an identity provider such as Okta or Google Workspace using SAML or OIDC. If your account is configured for SSO, you authenticate through your employer, and Brex does not prompt you separately for its own MFA while SSO is active. Passkeys do not replace SSO either. If sign-in suddenly behaves differently, ask your IT team before resetting passwords — the change usually happened at the identity-provider level.

![Security settings showing an authenticator app, recovery codes and a passkey being created](img-03.jpg)

## A Tour of the Brex Dashboard, Section by Section

Exact menu labels can change as the product evolves, but the functional areas below are what a Brex dashboard is organised around. Think of this as a map of capabilities rather than a screenshot transcription.

### The Home Overview

The landing view summarises the state of the business: recent spend, card activity, account balances and items needing attention such as missing receipts or pending approvals. For an admin, this is the morning-glance screen. A healthy account shows a short attention list; a neglected one shows a long one.

### Cards

The cards area lists every physical and virtual card in the company, who holds it, its status and its limit. From here admins issue new cards, employees view their card details, and anyone with permission can freeze a card instantly if it is lost or a suspicious transaction appears. Virtual cards deserve special attention: creating a dedicated virtual card per vendor (one for your cloud provider, one for your ad platform) makes cancelling a compromised or unwanted subscription a ten-second job instead of a card-replacement saga.

### Expenses and Transactions

Every swipe feeds the transactions list in near real time, with merchant, amount, cardholder and receipt status. Employees attach receipts — the mobile app can capture them at the till — and the platform matches them to transactions automatically. Finance teams can filter by person, department, card or date range, which turns "who bought this?" from an email thread into a five-second search.

### Budgets and Spend Limits

Beyond individual card limits, Brex organises spending into budgets for teams, departments or projects. This is where the platform's controls become genuinely useful: a marketing budget with a monthly cap, a travel budget with per-trip allowances, and automatic declines when a card is used outside its budget's rules.

### Accounts and Payments

This area covers the business account behind the cards — balances, transfers, bill payments and scheduled payments to vendors. It is the operational half of the product and the reason the platform is often described as a financial operating system rather than a card with an app.

### Rewards

Points earned across company spending accumulate here, along with redemption options such as cash back, statement credit, travel or gift cards, depending on your plan. More on maximising this in the rewards section below.

### Travel

Where enabled, travel booking and trip expenses live in their own area so that flights, hotels and per-trip cards stay grouped with the traveller rather than scattered through the general transaction feed.

### Settings and Team

Company settings, user management, roles and permissions, accounting integrations and security policies are administered here. This is also where admins invite employees, assign roles and deactivate leavers — a task that should be part of every offboarding checklist.

![The dashboard home overview with recent spend, balances and items needing attention](img-04.jpg)

## Cards, From the Dashboard User's Point of View

Everything in this section is written for the person staring at the screen: you need spend to happen, safely, without you personally approving every coffee. The [brex business credit card](https://brexcardadvisor.com/brex-business-credit-card) is a charge card, which means the balance is repaid in full on a daily or monthly cycle rather than revolving like a traditional [brex credit card](https://brexcardadvisor.com/brex-business-credit-card) product might. There is no personal guarantee — the company's finances, not the founder's credit file, underpin the account — and there is no annual fee for the card itself.

### Step by Step: Issuing a Card to a New Employee

1. **Open the cards area** of the dashboard and choose the option to issue a new card.
2. **Select the employee.** If they are not yet a user, invite them from the team settings first, with the correct role — an employee who only spends should not receive admin rights by accident.
3. **Choose physical or virtual.** Physical cards suit people who travel or buy in person; virtual cards are instant and ideal for online subscriptions and vendors.
4. **Attach the card to a budget** and set its limit (covered in the next section). A card without a budget is a card without a leash.
5. **Confirm and notify.** The employee receives their card details — virtual cards are usable immediately, physical cards arrive by post — and their own login lets them see exactly the limit you set. Transparency prevents the awkward "I didn't know" conversation later.

### Physical vs Virtual: A Practical Rule

Give everyone who spends regularly one physical [brex business card](https://brexcardadvisor.com/brex-business-credit-card) for the real world, and be generous with virtual cards for the digital world. The [brex corporate card](https://brexcardadvisor.com/brex-corporate-card) programme supports both from the same account and the same dashboard, so there is no administrative excuse for sharing one card number across a whole company — a habit that destroys your audit trail and makes fraud investigations miserable.

### Freezing, Replacing and Cancelling

From any card's detail view you can freeze it (reversible, instant, perfect for "I think I left it in a taxi"), unfreeze it when it turns up, or cancel and reissue when it is genuinely compromised. Do this from the mobile app at 2 a.m. if you must — the dashboard's card controls are deliberately the fastest tools in the product, because minutes matter when a card is lost.

![Issuing a new physical and virtual card to an employee from the cards section](img-05.jpg)

## Spend Limits: The Controls You Will Actually Use

A [brex corporate credit card](https://brexcardadvisor.com/brex-corporate-card) limit is not a borrowing limit in the traditional sense; it is a spending ceiling the company sets inside the boundaries Brex approves for the business. Understanding the two layers keeps expectations realistic.

### How the Ceilings Stack Up

Brex first approves an overall capacity for the company, based on its finances — cash position, revenue and account behaviour. Within that, admins distribute limits across budgets and individual cards. A card cannot spend beyond its own limit even if the company has capacity to spare, and a budget that is exhausted will decline transactions until an admin raises it or the period resets. Our full breakdown of how ceilings are calculated and raised is in the [guide to your card limit](https://brexcardadvisor.com/brex-card-limit).

### Step by Step: Setting a Sensible Limit

1. **Start from the role, not the person.** A travelling salesperson and a desk-based developer have predictably different spend. Create two or three standard limit tiers and assign people to them.
2. **Set the card limit inside the budget limit.** If the travel budget is the real control, keep card limits modestly above a typical trip cost rather than at the budget maximum.
3. **Use reset periods deliberately.** Monthly resets suit subscriptions and general spend; per-trip or one-off limits suit events and purchases. A one-off limit that expires is safer than a permanent high limit nobody reviews.
4. **Review the exceptions monthly.** Limit-raise requests are data: they show where budgets are unrealistic or where one team's costs are quietly ballooning.

### Temporary Raises Without the Drama

When a known big purchase is coming — a conference sponsorship, a hardware refresh — raise the specific card's limit temporarily instead of permanently. The dashboard makes this a short task, and lowering it afterwards returns the account to its normal risk posture. The discipline matters more than the feature: permanent high limits for everyone is how small companies end up with five-figure surprises.

![Setting a per-employee spend limit and budget cap inside the dashboard](img-06.jpg)

## Rewards and Brex Value, Seen From the Dashboard

Points are only valuable if someone actually redeems them, which is why the rewards area of the dashboard deserves a monthly visit rather than an annual one. The overall [brex value](https://brexcardadvisor.com/brex-card-rewards) proposition combines the points programme with the software itself: cards, expense automation, bill pay and travel in one subscription, replacing several tools a growing company would otherwise pay for separately.

### Where Points Come From

Company spending across cards earns points, with earn rates varying by category and plan. Because all spend flows through one platform, points pool at company level instead of fragmenting across individual employees' personal cards — one of the quiet financial arguments for moving company spend onto a single programme.

### Step by Step: Redeeming Points

1. **Open the rewards area** and check the current points balance and any expiring tranches.
2. **Compare redemption options.** Cash back and statement credit are the simplest to value; travel redemptions can be worth more per point for companies that fly often; gift cards occasionally carry bonus value during promotions.
3. **Redeem deliberately.** Pick the option your finance lead has agreed on as policy, so points do not evaporate into impulse redemptions.
4. **Record it properly.** Note the redemption in your accounting workflow the same day — points converted to statement credit change what the books should show.

Our deeper analysis of earn rates and redemption maths lives in the [rewards guide](https://brexcardadvisor.com/brex-card-rewards). The dashboard habit to build is simple: check the balance monthly, redeem quarterly, never let points expire unexamined.

![The rewards area showing a pooled points balance and redemption options](img-07.jpg)

## Fees: What the Dashboard Will (and Won't) Charge You

Fee transparency is one of the platform's stronger suits, and the dashboard reflects it: there is no annual fee for the [brexcard](https://brexcardadvisor.com), and the core Essentials plan is $0 while Premium costs $12 per user/month for companies that need the advanced controls. The full line-by-line picture is in our [fees breakdown](https://brexcardadvisor.com/brex-card-fees), but from a day-to-day operator's perspective, three things matter.

### What You Will See

Your subscription line, if you are on a paid plan, is predictable and per-user — which means it grows as you add seats, making the team list worth pruning of ex-employees and dormant accounts. Foreign transactions can carry a currency markup of up to around 3%, visible in transaction details, which matters for teams with heavy overseas software spend.

### What You Will Not See

Because the card is a charge card repaid in full, there is no revolving interest quietly accruing — the dashboard's job is to make sure the repayment account is funded, not to calculate APR. There are also no per-card issuance fees to track in the Essentials tier, which simplifies budgeting for larger teams.

### A Monthly Fee-Checking Routine

Once a month, whoever owns the dashboard should glance at three numbers: active billable users versus headcount, foreign-currency spend (and its markup), and any plan features you are paying for but not using. Ten minutes, three numbers, no surprises at renewal time.

![Reviewing subscription and transaction fee details in the accounts area](img-08.jpg)

## The Business Account Behind the Cards: The "Brex Bank" Question

New users often arrive searching for a [brex bank](https://brexcardadvisor.com/brex-business-account), sometimes typed as one word — [brexbank](https://brexcardadvisor.com) — expecting a standalone bank. What they actually get is more practical: Brex is a financial technology platform, and its business account functionality is delivered through partner banks rather than Brex being a chartered bank itself. The practical effect for the dashboard user is that cash management and card spend live side by side: money comes into the business account, card repayments flow out of it, and both appear in one ledger view.

### Day-to-Day Account Tasks

From the accounts area you can review balances, move money between accounts, set up payments to vendors and schedule recurring transfers. Bill pay deserves a special mention: paying a supplier invoice from the same dashboard that manages your cards removes the classic small-business split between "the card spreadsheet" and "the bank spreadsheet." For finance teams, pairing the account with the cards also smooths the daily or monthly repayment cycle — the funds are already where the charge card expects them.

### Treasury Habits for Admins

Treat the dashboard's account view as your cash command centre. Check the operating balance before large card repayment days, keep vendor payments scheduled rather than ad hoc, and reconcile the account feed weekly. The companies that get the most from the [brex business account features](https://brexcardadvisor.com/brex-business-account) are the ones whose bookkeeper works from the dashboard exports instead of reconstructing spend from three different statements.

![The business account view with balances, transfers and scheduled vendor payments](img-09.jpg)

## The Mobile App: Your Dashboard in a Pocket

The web dashboard is the office; the mobile app is the field kit. The same account email and authentication controls apply — password sign-in still goes through MFA, and passkeys and biometrics make phone sign-in genuinely fast.

### What Employees Actually Use It For

Capturing receipts is the killer feature. The app prompts cardholders after a transaction, they photograph the receipt, and the match happens automatically — killing the end-of-month shoebox of faded paper slips. Employees can also check their remaining limit before a purchase (far better than discovering a decline at a client dinner), freeze a lost card, and see exactly which expenses still need attention.

### What Admins Use It For

Approvals on the move. Limit-raise requests, expense approvals and suspicious-transaction alerts can all be handled from a phone, which keeps business spending unblocked even when the finance lead is travelling. If you manage a team, install the app and turn on notifications for approvals and card declines only — the two categories that block other people's work when ignored.

## Team Management, Step by Step

Cards and budgets only work if the people behind them are set up correctly. Team administration is unglamorous and absolutely critical.

### Step 1: Invite With the Right Role

Add users from the team settings with the minimum role they need. Typical distinctions are between administrators (full control), bookkeepers (visibility and exports without spending power), and employees (their own cards and expenses). Role discipline is a security control, not bureaucracy — most internal finance incidents trace back to someone having more access than their job required.

### Step 2: Assign Cards and Budgets on Day One

A new hire's onboarding should end with a card issued, a budget assigned and a five-minute tour of the app. People improvise with personal cards when the official path is slow, and every improvised purchase becomes a reimbursement claim and a missing-data problem.

### Step 3: Set Approval Rules

Configure who approves what: expenses above a threshold route to a manager, budget overruns route to finance, and everything is logged. The dashboard's audit trail then does compliance work for you — when an auditor asks who approved a payment, the answer is a link, not a memory.

### Step 4: Deactivate Leavers Immediately

When someone leaves, deactivate their user, cancel or reassign their cards, and remove them from billable seats in the same offboarding session. Former employees retaining active corporate cards is one of the most common — and most preventable — small-company fraud vectors. SSO-managed companies get help here: removing the person at the identity provider cuts Brex access too.

### A Note for Startups

Founders configuring a [brex corporate card for startups](https://brexcardadvisor.com/brex-for-startups) programme usually start as a team of three wearing every hat. Build the role structure anyway, even if one person holds all the roles today. The company that sets permissions properly at three people does not need a painful permissions overhaul at thirty — and funded startups with at least $50,000 in the bank are typically the ones Brex's underwriting is designed for, with requirements detailed in our [eligibility guide](https://brexcardadvisor.com/brex-card-requirements). For growing companies comparing [brex business credit cards](https://brexcardadvisor.com/brex-business-credit-card) against traditional bank offerings, the team controls are usually the deciding factor, not the plastic.

![Inviting a team member and assigning their role, card and budget](img-10.jpg)

## Troubleshooting: When Login or the Dashboard Fights Back

Even a smooth platform has bad days. Here are the most common problems, in the order a dashboard user actually meets them, each with a step-by-step fix.

### Problem 1: The MFA Code Never Arrives

1. Confirm which method is configured — app or SMS. People often wait for a text message when their account is set to authenticator app.
2. If SMS: check signal, disable airplane mode, and consider roaming if travelling. SMS delivery problems are usually carrier problems.
3. If app: check the device clock is set automatically; time-based codes fail when a phone's clock drifts.
4. Still stuck? Use a recovery code, or ask an admin to send a time-limited recovery code to your account email.

### Problem 2: Device Verification Keeps Failing

1. Use the link in the newest verification email — older links are superseded.
2. Check spam and corporate filters for messages from verifications@brex.com or noreply@brex.com, and ask IT to allowlist those senders.
3. If you use a VPN, complete the whole flow on one consistent connection: verification can fail when the IP address at sign-in differs from the IP address when opening the link.
4. Avoid private-browsing windows for the verification step; they discard the cookies the flow depends on.

### Problem 3: "Incorrect Password" You Are Sure Is Right

1. Check you are signing in with the exact account email — aliases and personal addresses are common culprits.
2. If your company uses SSO, use the SSO route; your Brex-specific password may not be the active credential at all.
3. Otherwise run the official password-reset flow and set a fresh, unique password. An admin can also trigger a reset for you from the team area — they never see your old password, and neither should anyone else.

### Problem 4: A Card Declined at the Till

1. Open the app or dashboard and look at the transaction — declines usually carry a reason.
2. Check the three usual suspects: the card's own limit, the parent budget's remaining balance, and whether the card is frozen or the budget excludes that category.
3. Fix the specific control (raise the limit, top up the budget, unfreeze) rather than issuing a new card. Declines are the control system working; your job is to adjust it deliberately, not bypass it.

### Problem 5: You Are Locked Out Entirely

Work through email access first — password resets and admin recovery codes both land in the account email, so regaining the mailbox unlocks everything else. If the email itself is gone (a departed employee's address, a decommissioned domain), the company's Brex administrator is the route back in. Brex will never phone you asking for a 2FA code; anyone who does is running a scam, however convincing they sound.

## Our Verdict From the Operator's Seat

Judged purely as a daily tool, the platform earns its place: sign-in is properly secured without being punishing, the dashboard organises the whole spend workflow in one place, and the mobile app removes the receipt-chasing that makes employees hate finance systems. Our complete scoring and methodology are in the full [brex card review](https://brexcardadvisor.com/brex-card-review), and readers weighing the platform against rivals should also read the [alternatives comparison](https://brexcardadvisor.com/brex-alternatives) — Ramp and traditional bank cards each win in specific scenarios, and honest operators should know where.

The deciding factor is rarely the feature list. It is whether your team will actually live in the dashboard. If they will — checking the feed, redeeming points quarterly, pruning users monthly — the platform compounds in value. If they won't, even the best card programme decays into another statement nobody reads.

## Frequently Asked Questions

### How do I find the Brex login page safely?

Bookmark the official site and use its sign-in option rather than search results. Legitimate sign-in happens on Brex's own domains (the dashboard and accounts subdomains). Never enter credentials or 2FA codes on a lookalike page, and remember a padlock icon does not prove a site is genuine.

### Can I use a passkey instead of a password and MFA?

Yes, if eligible. A passkey created in your personal security settings can replace both the password and the MFA step, authenticating with your device's Face ID, fingerprint, PIN or a hardware key. It does not replace a company SSO configuration.

### Why does Brex keep asking me to verify my device?

Device verification is a one-time authorisation per browser per device, but clearing cookies, using private browsing, or choosing "allow once" will trigger it again. Trust the device on machines only you use; never on shared computers.

### What is the difference between a card limit and a budget?

Brex approves an overall capacity for the company. Budgets allocate portions of that capacity to teams or purposes, and each card carries its own limit inside its budget. A transaction must satisfy all three layers to be approved.

### Does Brex charge an annual fee for its cards?

No — the card itself has no annual fee. The Essentials plan is $0 and Premium is $12 per user/month, with the main variable costs for most companies being per-seat subscription as the team grows and markups on foreign-currency transactions.

### Is Brex a bank?

No. Brex is a financial technology company founded in San Francisco in 2017 (and acquired by Capital One, with the acquisition completing in April 2026). Its business account services are delivered through partner banks, while the dashboard unifies the account, cards and spend tools in one interface.

### How do employees submit receipts?

Through the mobile app — photograph the receipt when prompted after a transaction and it is matched automatically — or by attaching it to the transaction in the web dashboard. Admins can see at a glance which transactions are still missing receipts.

### What should an admin do when an employee leaves?

Deactivate the user, cancel or reassign their cards, remove them from budgets and billable seats, and — if SSO is in use — remove them at the identity provider as well. Do it the same day; dormant cards belonging to ex-employees are an unnecessary risk.

### Can one person have both a physical and a virtual card?

Yes. Most companies give regular spenders one physical card for in-person purchases and multiple virtual cards for online vendors and subscriptions, all managed from the same dashboard and drawing on the same budgets.

## Conclusion: Small Routines, Serious Control

Mastering Brex is not about memorising every menu. It is about a handful of routines: sign in securely with MFA or a passkey, glance at the dashboard's attention list daily, issue and limit cards deliberately, redeem points quarterly, prune users monthly, and troubleshoot methodically when something breaks. Do those things and the platform quietly enforces your spending policy while you get on with running the business.

If you are still evaluating rather than operating, start with the fundamentals — what the card is, what it costs and whether your company qualifies — then come back here when the account is live and the dashboard is your new morning habit.

Originally published by Brex Card Advisor — https://brexcardadvisor.com

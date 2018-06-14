# 		About us
## 	What is a Retro Rabbit?

We are a software consultancy. We are technologists. We are agile.

Consultancy: We propose and implement software and technology that solve specific problems for our clients
Technologists: We are comfortable and familiar with a vast range of programming languages, platforms, systems, services, and integrations; i.e., collectively, technology.
Agile: We deliver working software early and frequently. We work closely with our clients. We embrace change. We continually improve our process. (Also means we _require_ client involvement; that it is difficult to track progress and virtually impossible to predict total dev time, partly due to dynamic requirement changes; slightly more time used up for refactoring due to limited scope of early versions)

# 		Proposed Project
## 	What we would like to build for you

Overview:
A lottery system with various draws (games), various access points for players, and critical tools for managing the system profitably.

Project features:
- Higher income players
- Lower income players
- Business owners

Project architecture

# 		Interface: Higher-income Players
## 	How do they access the game?

Higher-income players have access to smart phones and web browsers.
We will offer them:
- A responsive web app
- Mobile app

We will develop these mobile-first, meaning we will start with a responsive web app that works great on mobile.

# 		Features: Higher-income Players
## 	How will they play the game?

The website and the app will provide similar features.
For convenience, users can register accounts.

# 		Features for players with accounts

If a player registers an account, they will get the following conveniences:
- User-friendly authentication
- Stored payment methods
- Stored tickets
- Simple prize-claiming
- Token wallets
- Push notifiactions
- Stats for nerds

###	Authentication

An account can be linked to major authentication providers:
- Google/gmail
- Facebook
- Twitter
- Email + password
- Username + password

Multiple providers can be linked to a single account, allowing convenient authentication.
Some of these providers provide info about the registerer's age, but some might require the account to be fully activated at an authority with proof of age.

### 	Account-less usage

Users who don't want to create accounts can still use the system.
Payments are done per purchase (browsers may cache payment details; the app may be configured to do the same).
Tickets are received at any (combination of) methods:
- Email
- SMS
- Downloaded PDF

### 	Stored Payment Methods

A player can register payment methods, which can be used for instant payments.

### 	Stored tickets

Purchased tickets are stored to an account. 
A player can see all their tickets in one place.

### 	Prize claiming

Prizes can be claimed with the help of the web-app or app.
For small winnings that do not warrant in-person claims, the amount can be payed out to a linked card.
(For the Ithuba National Lottery, prizes under R2000 can be claimed at any outlet.)
For large winnings, user can:
- Get their tickets out of the app storage
	- as scannable QR codes (inside the app)
	- emailed to them
	- downloaded as PDF to be printed
- Get a filled-out claim form
(The Ithuba lotto requires one for larger winnings)

### 	Tokens instead of cash

The account has an associated token wallet.
To encourage users to take tokens, a prize pays out more in tokens than cash.
Tokens are used to buy more tickets.

### 	Push notifications

Users can be instantly notified about winnings
Users can be reminded about weekly draws, especially if they haven't bought tickets.
We can notify users about special jackpots etc.

### 	Stats for nerds

Interested users can check out the odds, the latest number of entrants, etc.

# 		Interface: Lower-income Players
## 	How do they access the game?

Lower income players may have feature phones and basic cell phones.
We will offer them:
- A simplified mobi website
- USSD and SMS menus
- Hardware terminals
- In-store purchases via teller systems

# 		Features: Lower-income Players
## 	How will they play the game?

### 	Feature phones

Signing in is still supported via providers, but interface is less convenient than on smart phones.
Payments are identical to high-income interfaces.
Tickets are received in the same way.

### 	Basic phones

Tickets are purchased via USSD or SMS menus.
The final purchase will be charged to the player using premium-priced USSD or SMS.
Tickets are sent to the player via SMS.
The system will support delivery reports, which will help in settling disputes.

### 	Terminals

Tickets are purchased at the terminal.
The terminal prints a slip.

### 	Tellers

Selected teller systems (at eg. garages) will have integrated software that will interact with our system.
Tickets are printed as slips.

# 		Interface: Business Owners
## 	How will you manage the system?

In order for you to manage the system successfully, we will provide:
- Stats, analytics and predictions
- Adjustable odds
- Communications and notifications for marketing
- Finance management

# 		Features: Business Owners
## 	How will it work?

### 	Stats, analytics and predictions

Sales reports
Sales per platform
Journey tracking
Sales predictions 
- For estimating prize amounts
- For estimating winner odds
Alerts when winner odds are too high

### 	Adjustable odds

As userbase grows, the odds of multiple people winning increase.
Manage the odds by adjusting the number of "balls".

### 	Communications

Notify users of upcoming games to increase sales.
Send important notices.

### 	Finance management

Track income and profits
Manage prize amounts

# 		Non-functional requirements
## 	What else can you expect from the system?

Aside from the features, the system will provide
- Scalability
- High availability
- Security
- Auditability

### 	Scalability

The system will be able to handle rapid growth to high volumes of user requests, as well as data.
// CRIP: high-availability load balancers
// CRIP: multi-site deployable architecture
// CRIP: horizontal scaling DBs

### 	High availability

Users will not experience down-time.
// TODO: how?

### 	Security

Tickets will be non-manufacturable.
// CRIP: how do we propose this
Draws cannot be tampered with or influenced.

### 	Auditability

Full reports will be generated and securely stored for all transactions and draws.

# 		System architecture
## 	How is the system structured?

// TODO: draw diagrams, but probably do it on the whiteboard
// TODO: make cripnotes about which techs to use, which alternatives exist, and the tradeoffs
// TODO: make criptnotes about scaling

# 		Timeframe
## 	How long will it take?

// TODO: give a timeframe for the whole system with a preferred team size
// TODO: how can it be made faster with more devs?
// TODO: how can it be made faster with less features?
// TODO: make cripnotes about MVP systems; don't present it though!

# 		Thank you
## 	Any questions?


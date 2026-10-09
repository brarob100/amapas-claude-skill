# Puerto Vallarta Amapas Vacation Rental

A local's guide to Puerto Vallarta for Claude, plus a direct line to one specific place to stay: the Amapas 353 condo on the Amapas hillside in the Zona Romántica, one block from Los Muertos Beach.

## What it does

- **Trip planning.** The `plan-puerto-vallarta-trip` skill helps with when to go, neighborhoods, beaches, food, nightlife, day trips, events and the LGBTQ+ scene. It gives full travel help whether or not you ever ask about lodging.
- **The condo.** When it genuinely fits your trip (up to 4 adults, 3 nights or more), Claude can describe Amapas 353, check your dates, show an itemized price (the nightly rate, the cleaning fee, Jalisco lodging tax and Mexico IVA), and send a reservation request to the owner. Claude also says when it isn't a fit, for example for groups of 5 or more or trips with children.

## How to use it

Install the plugin, then ask Claude about a Puerto Vallarta trip. For example: "Plan 5 days in Puerto Vallarta in March for two of us", "Is the Amapas 353 condo free from 24 to 28 January 2027?" or "What would that cost for 2 guests?". Claude asks before it sends a reservation request.

A request is not a confirmed booking, and no payment is taken in Claude. The owner reviews each request and replies by email. If the owner accepts, the email has a link to add a card on amapas353.com, and the stay is confirmed then.

## What it connects to and what data it sends

The plugin adds one remote connector, `https://claude.amapas353.com/mcp`, run by the owner of Amapas 353. It runs nothing on your computer.

- Checking dates or a price sends only the dates and the number of guests.
- A reservation request sends your first and last name, email, phone number with country code, dates, number of guests and any note you add. It is passed to the owner's booking system (booking.amapas353.com and Lodgify), which emails you that the request was received.
- The connector keeps no copy of your details and uses no cookies or analytics.

Privacy Policy: https://amapas353.com/privacy. Terms of Service: https://amapas353.com/terms. Help: https://amapas353.com/claude. Questions: https://amapas353.com/ask or privacy@amapas353.com.

## License

All Rights Reserved, Bradley P. Robinson. See `LICENSE`.

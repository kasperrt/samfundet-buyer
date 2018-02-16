## Samfundet Auto-ticket buyer

This is a simple automatic ticket-buyer for the site https://samfundet.no.

To start, run

``` $ npm install && npm start ```

Then navigate to http://localhost:3000, and enter your credentials, cardnumber, email, and url for the show (e.g. https://samfundet.no/arrangement/1475-elektrosamfundet).

If you want the app to automatically retry check the "Try till close app" (when this is enabled, you have to close the tab to break the loop, or be quick with unchecking the checkbox before it reloads).

Never use this over an open network, since this involves sending debitcard number, and all credentials to perform a purchase with it. The publisher of this code relieves himself from all responsibility for lost money, so use this app with caution. No money will be returned if something goes awry.

Since the code is more than shit, don't expect it to be bug-free.

Good luck with purchases!

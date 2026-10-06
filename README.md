# Front Street Salon &amp; Spa

A demonstration website for a full-service salon and day spa, built by
[Good Looking Digital](https://goodlookingdigital.com).

Front Street Salon &amp; Spa is a fictional business. The site exists to show what
a local salon's website can look like, not to take bookings for anyone.

## What it is

One static page. No build step, no framework, no backend, no database.

That is a deliberate choice rather than a shortcut. A salon's real conversion is
an appointment, and salons already run booking through Vagaro, Boulevard,
GlossGenius or Square. The website's job is to feed the system they already pay
for, so there is nothing here to compete with it, nothing holding customer data
and nothing to patch.

On a live client build the only server-side piece would be a single function to
deliver the enquiry form by email. Payments and card details stay with the
booking provider.

## Running it

Open `index.html`. There is nothing to install.

## Structure

    index.html        the whole site
    img/              photography, plus CREDITS.txt
    robots.txt        crawling allowed so the noindex can be read

## Design

Sage and cream with brass, Marcellus over Karla, spa led rather than salon led.
The page leads with the quiet rather than with a price list, because that is what
a day spa is actually selling.

Every photograph carries the same treatment in CSS, a slight desaturation and a
sage wash over each frame. The images are well matched but they are not from one
shoot, and without that treatment a set like this reads as assorted stock no
matter how good each picture is.

## Photography

Unsplash, under the Unsplash License. Source ids are listed in
`img/CREDITS.txt`.

A real client's site must use photographs of their own salon and their own work.
Stock imagery of a salon that is not theirs is a promise the business cannot
keep, and customers notice when they walk in.

## Kept out of search

The page carries `noindex, nofollow`, and `robots.txt` allows crawling on
purpose, because a crawler has to fetch the page to read the tag. Both come off
if the site is ever sold to a real business.

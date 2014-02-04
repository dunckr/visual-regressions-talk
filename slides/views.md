## Think about the views

note:
    you could argue that these are the most imporant part of the frontend
    they dont care if you have a bunch of spaghetti code or not

    but they are not being tested anywhere - where should they go?

    only place maybe would be the acceptance tests but they would be very brittle

    the acceptance tests the various users scenarios

    Yes, does this button exist and can I click it

    But what we are NOT testing how does it appear on screen and if it changes

    we dont want to start muddling that with css

    not practical if we are trying to quickly iterate or A/B test

    end up with alot of rewritten tests - not giving us much value

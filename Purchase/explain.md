Overview
    Once a seller has access to the "buy" button the process explained in these documents will occur
    This process will include
    - Charging the Customer with a new card, or one previously Saved
    - Store Changes in Firebase
    - Charging Seller


Concerns
    - At some point we will have to figure out how to modify this process for new users. As they won't have a userid to tie the stripe information to. 
    - Emails need to be sent after buyer wins to notifiy them to ship. This can be/should be done with webhooks
    - I believe the minumum allowed charge on stripe is about .50 cents so items can't be sold for less then that or a dollar






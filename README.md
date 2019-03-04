# Cat Ranker

A website for posting, ranking, and trading sweet cat pics. Upload your best friend today.

Concept:

* People have accounts (Users).
* Users upload cat pictures. Users own cat pictures.
* Users may _browse_ other people's uploaded cat pictures in a feed. Infinite scroll or pagination would be nice.
* Users may _vote_ on cat pictures. 
  * A _vote_ is one of (CHONKER, FLOOF, LOAF, POTATO, RARE, and NOT A CAT).
  * _votes_ award points to cat picture owners. (chonker, floof, loaf, potato) = 1 cat point. (rare) = 3 cat points. (not a cat) = -1 cat points.
  * Users have a balance of cat points, starting with 10. It costs nothing to vote. (should it?)
* Users may _bid_ on cat pictures with votes to obtain ownership.
  * Bids have amounts. A bidder may not bid more cat points than they have.
  * A cat picture owner must accept a bid to complete the transaction. 
  * When a bid is accepted, the bid amount is transfered from the bidder to the previous owner.
  * When future votes are placed on an individual cat picture, points are awarded to the new owner.
  * All previous points awarded per cat picture are awarded to whoever owned the picture at the given time.
* A master point ledger report can be obtained to see the entire cat point transaction history. 
* A global wealth report should also be possible.
* Users may buy cat points with real money. Something something credit card transactions. TBD.

## TODO:

1. Domain model
1. Scaffold it out
1. Test basic workflows with rails console
1. Write model logic to facilitate workflows with rails console
1. Build out controllers to faclitate workflows with apis
1. Decide on UI technology fidelity - full React implementation or minimal viable product? Use a UI system (salesforce/lightning, twitter/bootstrap, etc.)?1
1. Get system feedback
1. Iterate



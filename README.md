# RÖSTIMARKT



## Goal
A trading platform, where _vendors_ use _inters_ as selling points, and _consumers_ buy directly to _vendors_, while subscribing to a _inter_, used as delivery point.

The _consumers_ subscribe to a geographically close _inter_, and order items. If a condition( minimum quantity at deadline) is met, the deal is closed, and the _vendors_ delivers to the _inter_. Else, deal is cancelled.

Items are made available according to the _vendors_' stock. 
A commission is paid both to the site owner and the _inter_.


In addition to that, _vendors_ should be able to use that platform as well to monitor their own stock, and eventually to initiate trades. Trades will be completed offline, but the platform should provide a way for each to tell if they have overflow in a certain type of item.

## Specs

3 types of visitors: _vendors_, _inters_ & _consumers_.
A database listing all types of items available, each item constituted of: _name, description, image, season ..._
All users must be able to provide private feedback on other users, for admin purposes

#### _Vendors_:
Must be able to add items, constituted of

  - quantity
  - price
  - _inter_
  - _consumers_

Must be able to get some statistics about their sales and stocks.

#### _Consumers_:
Must have access to a list of items, and pay via the platform. Payment is closed only if deal was closed.
They can choose an _inter_ based on a location(through a map).

#### _Inters_:
Constituted of:

  - an address
  - a list of _consumers_ associated
  - a list of items provided by the _vendors_

###Platforms

_Consumers_ must be able to browse/buy on smartphone, no need for native app, though.

### Tech

Any technology is free to use
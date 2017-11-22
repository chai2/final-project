# Gravatar on Blockchain: Associate images with Bitcoin, Litecoin and Ethereum addresses

Description:

Inspired by Gravatar.com, want to implement something similar but on blockchain platform. Even though Gravatar added support for adding Bitcoin, Litecoin and Dogecoin addresses(https://en.gravatar.com/support/profile-crypto-currency/) to user profile, I would like to extend the idea and save all the information on Blockchain and use IPFS for persisting images and other information(more below). As part of my research I came across, Cryptavatar(https://cryptavatar.appspot.com/) that added ability to "Search" for a gravatar using coin address. I would like to implement these ideas into one application and build:

- Ability to add multiple coin addresses and associate user images.
- Store all the static assets on IPFS.
- Assets accessible using IPNS entry.
- Users can choose a subscription plan Yearly or Monthly. If subscription expires, the assets will not be served. (Smart contracts for subscriptions and renewals)
- Expose public endpoints to retrieve metadata info for a specific user.

Users paying for subscription is used to support and incentivize ipfs peers and network node to be operational.

TDB:

- Authentication system

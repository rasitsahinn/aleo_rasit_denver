# Auction Program
This is a Leo-based auction program where participants can place bids, and the auction runner selects the highest bid. The winner's ownership is transferred upon completion.

## Features
- **Bid Placement**: Users can place bids, which are recorded securely.
- **Winner Selection**: The auction runner determines the highest bid as the winner.
- **Ownership Transfer**: The winning bid is assigned to the respective bidder.

## Functions
### `place_bid(bidder: address, amount: u64) -> Bid`
Places a bid with the given bidder address and bid amount.

### `resolve(first: Bid, second: Bid) -> Bid`
Compares two bids and selects the higher bid as the winner.

### `finish(bid: Bid) -> Bid`
Finalizes the auction by transferring ownership to the winner.

## Auction Runner
The auction is managed by a predefined address, which has the authority to resolve bids and complete the auction.

## License
This project is open-source and available for use under the MIT License.


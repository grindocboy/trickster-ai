# Trickster AI Games

Browser-based practice games under one banner:

- Trickster AI: Learn Spades
- Trickster AI: Learn Blackjack
- Trickster AI: Learn Poker

## Play Online

### [Play Trickster AI Games](https://grindocboy.github.io/trickster-ai/)

Choose Spades, Blackjack, or Poker from the main game launcher.

Direct game links:

- [Play Spades](https://grindocboy.github.io/trickster-ai/spades.html)
- [Play Blackjack](https://grindocboy.github.io/trickster-ai/blackjack.html)
- [Play Poker](https://grindocboy.github.io/trickster-ai/poker.html)

## Spades v0.8.0

- Four-player partnership Spades against AI opponents
- Full bidding from Nil through 13
- Configurable table rules and scoring options
- Partner-aware AI play
- Legal-play enforcement with follow-suit validation
- Spade-breaking rules
- Nil and Blind Nil support
- Bag tracking and bag-penalty scoring
- Team contract and trick tracking
- Bidding recommendations and in-hand AI coaching
- Detailed hand grades and performance feedback
- Bid, contract, play, bag-control, rules, and partner scoring
- Strengths and improvement notes after each hand
- Hand replay and decision review
- Responsive desktop and mobile card-table layout
- Persistent match progress in the browser

## Blackjack v0.2.0

- Six-deck persistent shoe and configurable casino rules
- Hit, stand, double, split, surrender
- Insurance and even money
- Basic-strategy coaching
- Selected Hi-Lo true-count deviations
- Card-count and true-count drills
- Animated dealing
- Detailed round grade
- Last-round replay and decision audit
- Strategy quick chart
- Local browser statistics

## Poker v0.1.3

- Four-player no-limit Texas Hold’em
- Three AI opponents
- Preflop, flop, turn, river, and showdown play
- Fold, check, call, and raise actions
- Rotating dealer, small blind, and big blind
- Complete poker-hand evaluation with split-pot and kicker comparisons
- Opponent cards hidden until showdown
- Detailed AI showdown coaching
- Timed action lessons explaining fold, check, call, and raise
- Starting-hand reference guide
- Persistent bankroll and session statistics
- Responsive desktop and mobile layout

## Run Locally

Open `index.html`, or run:

```bash
python3 -m http.server 8000
```

Then visit `http://localhost:8000`.

## GitHub Pages

The site is published from the repository root:

**https://grindocboy.github.io/trickster-ai/**

To configure deployment in GitHub, open **Settings → Pages**, choose **Deploy from a branch**, then select `main` and `/(root)`.

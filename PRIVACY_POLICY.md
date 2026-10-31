# Privacy Policy for The Found Merchant

**Effective date: October 31, 2026**

## Overview

The Found Merchant is a private Chrome extension used to enhance a D&D Beyond campaign with synchronized merchant features and a shared combat initiative display on D&D Beyond character sheets.

## Information the extension accesses

When used on a supported D&D Beyond character sheet, the extension may read game-related character information displayed on that page, including the character name, portrait, race, class, level, currency, and inventory information needed to provide the merchant features.

When used on a supported D&D Beyond Maps Spectator View, the extension may read the combat initiative tracker displayed on that page, including combatant names, portraits, initiative order, current-turn state, and the visual tracker information needed to reproduce the tracker on participating character sheets.

The extension also processes campaign merchant settings, inventory, transaction information, storefront state, and extension preferences that are necessary to provide its features.

The extension does not request or collect D&D Beyond passwords, payment-card information, or general web-browsing history.

## How information is used

The accessed information is used only to provide The Found Merchant's campaign features, including displaying merchant storefronts, processing in-game purchases and currency updates, synchronizing merchant/session state, and displaying the current D&D Beyond combat initiative tracker on participating character sheets.

Initiative information is hidden by default on a character sheet until the player chooses to show it. The player's show/hide preference is stored locally by the extension.

## Storage and synchronization

The extension uses Chrome extension storage for local extension settings and preferences.

Campaign merchant/session information and the current combat initiative state are synchronized using Google Firebase Firestore so the Dungeon Master and participating players can share the same campaign state across supported D&D Beyond pages.

The current initiative state is updated as combat changes and is used to provide the live initiative display; the extension is not designed to maintain a historical archive of initiative turns.

Data transmitted to Firestore is sent over HTTPS.

## Data sharing

The Found Merchant does not sell user data and does not share user data with advertisers or data brokers.

Data is shared only with service providers required to operate the extension, including Google Firebase/Firestore for synchronization, and only for the purposes described in this policy.

D&D Beyond is the source of the game information displayed on supported pages; The Found Merchant is not affiliated with or endorsed by D&D Beyond or Wizards of the Coast.

## Analytics and advertising

The extension does not include advertising and does not use collected campaign data for advertising or cross-site tracking.

## Data retention

Local extension settings remain in Chrome extension storage until they are changed, cleared, or the extension is removed.

Campaign data stored in Firestore is retained only as needed to operate the campaign features. Current initiative state is overwritten as combat state changes rather than being intentionally retained as a turn-by-turn history.

## Security

The extension is designed to limit access to information needed for its campaign features and uses encrypted HTTPS connections when communicating with Firebase/Firestore.

## Children's privacy

The Found Merchant is not designed to knowingly collect personal information from children under 13. The extension processes game-related campaign information only as described above.

## Changes to this policy

This policy may be updated when The Found Merchant's features or data practices change. The effective date at the top of this policy will be updated when material changes are made.

## Contact

Questions about this privacy policy may be submitted through the support/contact method provided on The Found Merchant's Chrome Web Store listing.

# How to Change RTP (Return to Player)

## Who this article is for
This guide is intended for Platform Administrators, Game Operations teams, and Technical Support teams responsible for game configuration.

## Overview
Return to Player (RTP) is a predefined percentage that indicates the expected payout of a game over time. RTP values are configured at the platform or game-provider level and may vary depending on jurisdiction, certification, and operator settings.

This document describes the standard process for updating RTP settings for supported games.

## Prerequisites
Before changing RTP, ensure that:
- You have administrative access to the back-office system
- The selected RTP value is certified for the target jurisdiction
- The game provider supports multiple RTP configurations
- No active incidents or game outages are in progress

## Step-by-step instructions
1. Log in to the **Back Office** system.
2. Navigate to **Games Management** → **Game Configuration**.
3. Select the required **Game Provider**.
4. Choose the specific **Game** from the list.
5. Open the **RTP Settings** section.
6. Select the desired RTP value from the available options.
   - Example values: 95%, 94% **(only integer values are supported)**
7. Confirm the configuration change.
8. Save the updated settings.

## Verification
After updating the RTP:
- Refresh the game configuration cache.
- Launch the game in a test environment.
- Confirm that the correct RTP value is displayed in the game settings or logs.

## Important Notes
- RTP changes do not affect individual game rounds.
- Changes apply only to new game sessions started after the update.
- RTP values cannot be customized beyond provider-certified options.

## Troubleshooting

### RTP option is not available
- Verify that the selected RTP is enabled for the jurisdiction.
- Confirm with the game provider that the RTP configuration is supported.

### RTP change not applied
- Check cache synchronization status.
- Restart the game session.
- Review platform logs for configuration errors.

## Compliance Considerations
All RTP changes must comply with regulatory requirements and internal approval processes. Unauthorized changes may result in compliance violations.

## Notes
> This document is a fictional example created for portfolio purposes only. It does not represent any real system, platform, or configuration.


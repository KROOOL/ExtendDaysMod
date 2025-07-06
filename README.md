# ExtendDaysMod
A Lethal Company mod that dynamically extends the deadline based on your profit quota.

For every **$200** earned in the quota, you gain **+1 day** to complete the deadline (up to a maximum of **5 extra days**). This gives players more time to complete higher quotas and encourages pushing limits.

Compatible with V47 and all other mods (i think). Also fully compatible with **LethalConfig** for custom configuration!

Any issue or bug, pls tell me!

## Configuration

By default:
- **QuotaPerDay** = 200  
- **DayExtension** = 1 (days per block)  
- **MaxExtraDays** = 5  

You can tweak these in:
- **BepInEx `config.yaml`** under the `[ExtendDays]` section  
- **LethalConfig UI** (if installed) under *ExtendDays -> ExtendDaysMod Settings*

### Thunderstore App (Recommended)
1. Search for `ExtendDaysMod` in the Thunderstore mod manager
2. Click **Install**
3. Enable it in your profile and play!

## Manual Installation
1. Install BepInEx
2. Install ExtendDays (https://thunderstore.io/c/lethal-company/p/KROOOL/ExtendDays/)
3. Install LobbyCompatibility (https://thunderstore.io/c/lethal-company/p/BMX/LobbyCompatibility/)
4. (Optional) Install LethalConfig (https://thunderstore.io/c/lethal-company/p/AinaVT/LethalConfig/)
5. Extract ExtendDaysMod.dll and LobbyCompatibility into the plugins folder of BepInEx

## Credit
- KROOOL - Programmer
- Redgar - Testing lol

## Changelog
- **1.1.o** - Compatibility with **LethalConfig**

*Enjoy the extra time!*
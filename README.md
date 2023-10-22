# HL2VRU

> **Half-Life 2: VR Mod - Unleashed**
>
> Unofficial fork of the excellent [HL2VR](https://halflife2vr.com/) mod focused on implementing unique VR-only interactions and providing more freedom to the player.

## New Features

* **Universal melee**
    - ➡️ | Allows physical melee attacks with any weapon, or even with empty hands.
    - 🛠️ | Can be toggled in the *tweaks menu*, the damage can also be tuned as well.

* **Physical jumping**
    - ➡️ | Translates physical jumping into in-game jumping.
    - 🛠️ | Can be toggled in the *controls menu*.
    - 🛠️ | Jumping threshold can be tweaked via the `hlvr_control_physical_jump_threshold` CVar.

* **Dual wielding**
    - ➡️ | Allows each hand to independently equip and operate a weapon.
    - ⚠️ | Requires the following actions to be bound on *both* controllers in the SteamVR bindings menu:
        - `"Fire"`, `"Alt Fire"`, `"Eject Magazine"`, `"Open Weapon Selection"`
    - ⚠️ | It is recommended to change the default `"Toggle Menu"` action to be a long press or a chord to not interfere with the left hand's `"Alt Fire"` action.
    - ⚠️ | It is also recommended to disable the `"Sprint"` action when pressing the left hand's joystick, as that will become the most natural bind for the weapon selection HUD. Sprinting is still possible by double-tapping the joystick.
    - 🛈 | At the moment, obtaining any weapon makes it available for both hands. For example, as soon as you collect the crowbar, you'll be able to dual wield crowbars despite only having collected one.

* **Virtual stock**
    - ➡️ | Interpolates the two-handed aiming angle with the player's approximate shoulder position, resulting in more stability when aiming down sights.
    - 🛠️ | Can be toggled in the *tweaks menu*, where also the shoulder position can be tuned.

* **Grip-holster mode**
    - ➡️ | Automatically holsters weapons if the grip button is released, and automatically equips the last holstered weapon if the grip button is held.
    - 🛈 | Any hand interaction (e.g. grabbing a prop, toggling the flashlight) takes priority over equipping the last holstered weapon.
    - 🛈 | This is the recommended setting when dual wielding, as it simplifies the reloading process for two weapons a lot.
    - 🛈 | This setting also helps to quickly interact with the world (e.g. collect an item, climb a ladder) without having to open the weapon selection menu.
    - 🛈 | This setting is compatible with the *"Toggle grab"* option, that, if enabled, will require simply pressing the grip button rather than keeping it held.
    - 🛠️ | Can be toggled in the *controls menu*, where the related *"Toggle grab"* option can also be tuned.

* **Difficulty tweaks**
    - ➡️ | Allows fine-tuning of damage, recoil, and bullet spread.
    - 🛈 | Both inflicted and taken damage can be tuned, allowing a more deadly and intense (i.e. no bullet sponges) yet fair experience.
    - 🛈 | It is recommended to reduce the recoil multiplier a bit to make dual wielding automatic weapons more enjoyable. 
    - 🛠️ | Can be tuned in the *tweaks menu*.

## Installation

1. Install the original [Half-Life 2: VR Mod](https://store.steampowered.com/app/658920/HalfLife_2_VR_Mod/) from Steam.

2. Obtain the latest release of HL2VRU [from the "Releases" page](https://github.com/vittorioromeo/HL2VRU/releases).

3. Extract all the files on top of your existing HL2VR installation.
    - Usually `C:\Program Files (x86)\Steam\steamapps\common\Half-Life 2 VR\`.

4. Run HL2VR as normal. If the mod was successfully installed, the title screen should show *"U N L E A S H E D"* under the main title.

5. ❗❗ **Make sure to change your SteamVR bindings to support the new features**, and to tweak any settings. ❗❗

## Removal

1. In your Steam library, right-click on *"Half-Life 2: VR Mod"* and open *"Properties"*.

2. Press *"Verify integrity of game files"* and let Steam re-download the original files.

## Known issues

- When loading an existing save file created prior to the installation of HL2VRU, the player's left hand will not have any weapon available. They must be collected again, or added through a console command.

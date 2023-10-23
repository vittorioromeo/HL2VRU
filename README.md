# HL2VRU | Half-Life 2: VR Mod - Unleashed

> **Unofficial fork of the excellent [HL2VR](https://halflife2vr.com/) mod, implementing unique VR-only interactions and providing more freedom to the player.**

<div align="center">
  <a href="https://www.youtube.com/watch?v=6mhm5HpMduY"><img src="https://img.youtube.com/vi/6mhm5HpMduY/0.jpg" alt="Half-Life 2: VR Mod - Unleashed | Release Trailer"></a>
  <p><a href="https://www.youtube.com/watch?v=6mhm5HpMduY">Half-Life 2: VR Mod - Unleashed | Release Trailer</a></p>
</div>

## New Features

* **Universal Melee**
    - ➡️ | Allows physical melee attacks with any weapon, or even with empty hands.
    - 🛠️ | Can be toggled in the *tweaks menu*, the damage can also be tuned as well.

<p></p>

* **Physical Jumping**
    - ➡️ | Translates physical jumping into in-game jumping.
    - 🛠️ | Can be toggled in the *controls menu*.
    - 🛠️ | Jumping threshold can be tweaked via the `hlvr_control_physical_jump_threshold` CVar.

<p></p>

* **Dual Wielding**
    - ➡️ | Allows each hand to independently equip and operate a weapon.
    - ⚠️ | Requires the following actions to be bound on *both* controllers in the SteamVR bindings menu:
        - `"Fire"`, `"Alt Fire"`, `"Eject Magazine"`, `"Open Weapon Selection"`.
    - ⚠️ | It is recommended to rebind `"Toggle Menu"` to be a long press or chord to not interfere with left hand `"Alt Fire"`.
    - ⚠️ | It is also recommended to unbind `"Sprint"` on the left hand, as that is the most natural bind for weapon selection. Sprinting is still possible by double-tapping the joystick.
    - 🛈 | Obtaining a weapon makes it usable by both hands. E.g., as soon as you collect the crowbar, you'll be able to dual wield crowbars.

<p></p>

* **Virtual Stock**
    - ➡️ | Interpolates two-handed aiming with the player's approximate shoulder position, giving more stability when aiming down sights.
    - 🛠️ | Can be toggled in the *tweaks menu*, where also the shoulder position can be tuned.

<p></p>

* **Grip-Holster Mode**
    - ➡️ | Automatically holsters weapons when the grip is released, and equips the last holstered weapon when the grip is held.
    - 🛈 | Any hand interaction (e.g. grabbing a prop, using the flashlight) takes priority over equipping the last holstered weapon.
    - 🛈 | This is the recommended setting when dual wielding, as it simplifies the reloading process for two weapons a lot.
    - 🛈 | Helps to quickly interact with the world (e.g. collect an item, climb a ladder) without having to open the weapon selection menu.
    - 🛈 | Compatible with the *"Toggle grab"* option, that, if enabled, will require simply pressing the grip button rather than keeping it held.
    - 🛠️ | Can be toggled in the *controls menu*, where the related *"Toggle grab"* option can also be tuned.

<p></p>

* **Difficulty Tweaks**
    - ➡️ | Allows fine-tuning of damage, recoil, and bullet spread.
    - 🛈 | Both inflicted and taken damage can be tuned, allowing a more deadly and intense (i.e. no bullet sponges) yet fair experience.
    - 🛈 | It is recommended to reduce the recoil multiplier a bit to make dual wielding automatic weapons more enjoyable. 
    - 🛠️ | Can be tuned in the *tweaks menu*.
 
<p></p>

* **Miscellaneous**
    - ➡️ | Manually tweaked the offset of every weapon to keep the player's hand in the same position, improving aiming consistency.

## Installation

1. Install the original [Half-Life 2: VR Mod](https://store.steampowered.com/app/658920/HalfLife_2_VR_Mod/) from Steam.
    - Optionally, install [Half-Life 2: VR Mod - Episode One](https://store.steampowered.com/app/2177750/HalfLife_2_VR_Mod__Episode_One/) and [Half-Life 2: VR Mod - Episode Two](https://store.steampowered.com/app/2177760/HalfLife_2_VR_Mod__Episode_Two/).

<p></p>

2. Obtain the latest release of HL2VRU [from the "Releases" page](https://github.com/vittorioromeo/HL2VRU/releases).

<p></p>

3. Extract all the files on top of your existing HL2VR installation.
    - Usually `C:\Program Files (x86)\Steam\steamapps\common\Half-Life 2 VR\`.

<p></p>

4. Run HL2VR (or HL2VR:EP1/2) as normal from Steam.
     - If the mod was successfully installed, the title screen should show *"UNLEASHED"* in the logo.

<p></p>

5. ❗ **Make sure to change your SteamVR bindings to support the new features**, and to tweak any settings. ❗

## Removal

1. In your Steam library, right-click on *"Half-Life 2: VR Mod"* and open *"Properties"*.

2. Press *"Verify integrity of game files"* and let Steam re-download the original files.

## Known Issues

- When loading an existing save file created prior to the installation of HL2VRU, the player's left hand will not have any weapon available. They must be collected again, or added through a console command.

## Support The Project

- Buy the SourceVR team a coffee:
    - https://ko-fi.com/sourcevrmodteam

<p></p>

- Buy me a coffee:
    - https://github.com/sponsors/vittorioromeo
    - https://patreon.com/vittorioromeo
    - https://paypal.me/romeovittorio

## Other Projects

- [Quake VR](https://vittorioromeo.com/quakevr)
    - *"The timeless classic from 1996, reimagined for virtual reality."*

<p></p>

- [Open Hexagon](https://store.steampowered.com/app/1358090/Open_Hexagon/)
    - *"Four buttons, one goal: survive. Are you ready for a real challenge?"*

# 16-Levels-LPPMK3-M4L
## 16 Levels of Velocity - A Max For Live Patch For Novation Launchpad Pro MK3

### Requires Ableton Live 10+ with Max For Live installed (Max 8.1+) and Novation Launchpad Pro MK3 (LPPMK3)

Inspired by [One Tip for Better Drums](https://www.youtube.com/watch?v=1DH_eSiX6ls) by [Ricky Tinez](https://www.youtube.com/channel/UC4OAAbxtB6QEKaTDb-SEe-Q), 16 Levels of Velocity is a Max For Live Patch + LPPMK3 custom mode which enables an [MPC 16 Levels](https://www.youtube.com/channel/UC4OAAbxtB6QEKaTDb-SEe-Q)-like workflow for triggering velocity in Ableton Live.

Combined with Ableton Live [Step Recording](youtube.com/watch?v=yHLxwqSDWTQ), step entry of drums with velocity has never been easier!

### How To Use:
1. Install included "16 Levels" mode (syx file) with Novation Components (Upload Custom Mode), then send to the target LPP MK3.
2. Add this M4L Patch to a free midi channel by itself (no instruments).
3. Set MIDI From on the target Instrument channel (drum rack for example) to the channel with this patch.
4. Set Monitor In for both MIDI channels (16 Levels + Target).
5. Use Keyboard at the top or pad to the bottom left of the LPP to select key, and play single note with the 16 Levels of velocity on the right pad.
6. Change octaves of the key select keyboard & pads with the white strip under the keyboard.
7. Set a fixed velocity for the key select pads and keyboard with the switch in the UI.

### Limitations and notes
- Due to the nature of MIDI connectivity to Ableton Live, there's no built-in "16 Levels" of pitch or other control value within an Ableton drum rack like a real MPC. To emulate these features, map velocity to a control in an instrument that supports custom velocity to parameter mapping (Kontakt for instance).
- Because of limitations with Ableton Live's MIDI implementation, C -2 through B -1 are reserved for the 16 levels mode. This is because Live only supports 1 channel of MIDI per instrument channel. Thus the 16 level grid must take up some of the MIDI channel data.
- Because Ableton Live doesn't support recording of MIDI post-effects on the same instrument channel, this patch must be on its own instrument channel and be routed to the target instrument during recording.
<PERSONA_FILE>
PERSONA.md
</PERSONA_FILE>

<PROJECT_INFO>
**Name**: FlightDeck Framework
**Description**: A modular platform for building web-based DJ consoles and audio instrument panels. Powered by Brain AV and AVDJ.ca.
**Repository**: https://github.com/jasonbra1n/FlightDeck-Framework
</PROJECT_INFO>

<TECH_STACK>
- **Frontend**: HTML5, CSS3 (Custom UI)
- **Logic**: JavaScript (ES6+)
- **Audio Engine**: Web Audio API
- **Libraries**: jsmediatags (ID3 tag parsing)
</TECH_STACK>

<CODING_CONVENTIONS>
- **JS**: Use modern ES6+ syntax. Keep audio graph logic modular.
- **CSS**: Maintain strict naming for UI components to match the hardware layout.
- **Commits**: Follow Conventional Commits (feat, fix, docs, style, refactor).
</CODING_CONVENTIONS>

<CONTEXT_NOTES>
This project aims to be a faithful recreation.
- **Pitch Control**: Must handle real-time playback rate adjustment (-10% to +10%).
- **Cues**: Logic must support setting and recalling cue points accurately.
- **UI**: The interface should mimic the physical unit's layout and feedback (LEDs, display).
</CONTEXT_NOTES>
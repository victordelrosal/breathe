PRD: Zen Breathing Orb
Purpose
A single-page breathing meditation tool to help users oxygenate through guided visual breathing cues.
Core Experience

Single animated orb that morphs shape (expand on inhale, contract on exhale) in a slow, hypnotic breathing rhythm (~4s in, ~6s out)
Color gradient slowly cycles through purples → cyan → emerald green (independent of breathing cycle)
Text overlay displays "Breathe In" / "Breathe Out" synchronized with orb expansion/contraction

UI Components
Sticky Navbar:
ElementFunctionLanguage selectorDropdown with top 25 world languages; translates breathing textTheme toggleLight/dark modeRadio toggleCycles through 4 ambient stations
Radio Stations:

https://radio.hearme.fm:8152/stream
https://radio.hearme.fm:8148/stream
http://nap.casthost.net:8793/stream/1/
https://radio.hearme.fm:8188/stream

Technical Constraints

Single HTML file (inline CSS + JS)
No external dependencies except fonts (optional)
Smooth CSS/JS animations (requestAnimationFrame or CSS keyframes)
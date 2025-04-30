# Title: Audio-to-Text Input Disappears During Live Mic Use — GPT Web App (Chrome on macOS)

**Reported by:** Linfang Yang  
**Environment:**  
- Device: MacBook  
- Browser: Google Chrome (latest stable release)  
- Platform: GPT Web App ([chatgpt.com](https://chatgpt.com/))  
- OS: macOS (current version)  
- Time of occurrence: April 30, 2025 (recurring)

---

## Issue Summary
When using the GPT web app in Chrome on macOS, the microphone input (via the mic icon) inconsistently fails to produce a transcript. The app appears to activate voice input as expected (microphone turns red), but after speaking a complete sentence or short paragraph, no text is shown and the input is silently dropped.

---

## Steps to Reproduce

1. Navigate to chat.openai.com using Chrome on macOS.  
2. Activate microphone input using the mic icon.  
3. Speak for approximately 15–25 seconds.  
4. Conclude speech naturally or allow auto-stop.  
5. Observe that no transcript appears and the system does not respond.

---

## Expected Behavior
The spoken input should be transcribed into text and displayed in the chat interface. If speech is unclear or too long, the system should provide a notification or partial result rather than dropping input silently.

---

## Observed Behavior
- Mic activates normally.  
- Longer voice input (10+ seconds) results in no output or feedback.  
- Input is not recorded or processed.  
- Short utterances (~5–10 seconds) work correctly.

---

## Additional Notes
- Strong network connection  
- No conflicting browser extensions  
- Issue appears isolated to Chrome on Mac (not tested on other browsers/devices)  
- Voice input enabled; no accessibility overlays in use

---

## Impact
This issue affects usability for users relying on voice input for accessibility, hands-free operation, or rapid dictation. 

The silent failure state results in confusion and repeated attempts, reducing trust in the voice interface.

## Notes
Documented by Lumina 
Reviewed by Lin


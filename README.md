# System 1 agents, live: choosing from a short list

A small static page for the talk *Using AI Agents in Web Browsers* (Serat Saad, NASA AI/ML STIG, 28 September 2026).
The same model answers the same question twice: once by **choosing** one option (a single output token, read as
probabilities, with the options shown in several orders and averaged), and once by **writing** its answer.

- **One browser step:** the numbered controls JEV's loop saw on SIMBAD, arXiv, VizieR, ADS, NED and the ESO archive,
  recorded at the first step of runs that succeeded; the model picks the next control.
- **Galaxy morphology:** SDSS images of Galaxy Zoo 2 galaxies with clear volunteer majorities
  (Willett et al. 2013, MNRAS 435, 2835; VizieR J/MNRAS/435/2835). Images from SDSS SkyServer DR18.
- **Spectra:** SDSS DR18 optical spectra, plotted without labels; star, galaxy or quasar, with the SDSS
  spectroscopic class as the answer key.

The page holds no API key. To run it, paste an OpenAI API key into the field at the top; it stays in the page's
memory, is sent only to api.openai.com, and is not saved.

Live page: https://seratsaad.github.io/system1-demos/

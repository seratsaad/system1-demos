# System 1 demos: choosing from a short list, live

A small static page for the talk *Using AI Agents in Web Browsers* (Serat Saad, NASA AI/ML STIG, 28 September 2026).
The same model answers the same question twice: once by **choosing** one option (a single output token, read as
probabilities, with the options shown in several orders and averaged), and once by **writing** its answer.

- **arXiv categories:** papers from the astro-ph "new" listing; the answer key is each paper's primary category.
- **Galaxy morphology:** SDSS images of Galaxy Zoo 2 galaxies with clear volunteer majorities
  (Willett et al. 2013, MNRAS 435, 2835; VizieR J/MNRAS/435/2835). Images from SDSS SkyServer DR18.

The page holds no API key. To run it, paste an OpenAI API key into the field at the top; it stays in the page's
memory, is sent only to api.openai.com, and is not saved.

Live page: https://seratsaad.github.io/system1-demos/

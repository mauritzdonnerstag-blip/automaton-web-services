# Customer intake and pilot website

This repository contains the public-facing Phase 7 website-review pilot. It is **not** the private Automaton source repository.

## Files
- `.github/ISSUE_TEMPLATE/website-review.yml`: public customer request form
- `.github/ISSUE_TEMPLATE/config.yml`: hides blank issues for external visitors
- `docs/index.html`: optional public GitHub Pages landing page

## Activate
1. Review and merge the pull request adding these files.
2. Confirm that repository **Settings → General → Features → Issues** is enabled.
3. Visit **Issues → New issue** and select **Request a website review**; confirm all required fields are visible. Do not submit personal data during testing.
4. Enable GitHub Pages under **Settings → Pages** using **Deploy from a branch**, branch `main`, folder `/docs`, then confirm the deployment. Expected address (verify live): https://mauritzdonnerstag-blip.github.io/automaton-web-services/
5. Use the landing-page button to check that it opens the correct form.

## Safety and operational boundaries
- All GitHub issues and replies are public. Do not request or store sensitive personal information, secrets, client account credentials, or private-site URLs.
- Only use explicitly approved public URLs in the Phase 7 local `PHASE7_TARGETS.json` file.
- GitHub issue submissions are **not yet connected to Automaton automatically**. The operator must explicitly approve a target and place it in the local target file.
- Producing an HTML snapshot is not a professional certification. Review every finding before sharing.
- Do not automatically contact site owners, promise fulfillment or accept payments as part of this pilot.

## Local Phase 7 target file
The worker in `~/automaton` reads `PHASE7_TARGETS.json`. Start with the W3C Before/After Demo (BAD), which is provided for evaluation practice:
- https://www.w3.org/WAI/demos/bad/before/home.html
- https://www.w3.org/WAI/demos/bad/after/home.html
- https://the-internet.herokuapp.com/broken_images (public web UI test page)

These are **test sites, not business prospects**, and none implies permission to send sales messages.

# Anirudh Kamath

Builder. FDE-oriented. I ship on-device products, computer-vision pipelines, and agent evals.

## HeyGen HyperFrames

Merged PR in [heygen-com/hyperframes](https://github.com/heygen-com/hyperframes) (42k+ stars):

**[fix(studio): capture the storyboard frame hero at full resolution](https://github.com/heygen-com/hyperframes/pull/3338)**

I opened [#3271](https://github.com/heygen-com/hyperframes/issues/3271) with a reproduction: Studio storyboard posters were capped at 240x135, so the frame-detail hero upscaled a thumbnail and body copy went unreadable. Co-authored the merged fix so that surface captures at composition resolution.

## BallHog CV

Made-shot detection and highlight pipeline. Full game in, verified makes out.

Repo: [anikam13/ballhog-cv](https://github.com/anikam13/ballhog-cv)

![xdq demo](https://raw.githubusercontent.com/anikam13/ballhog-cv/main/docs/demo.gif)

![tnc demo](https://raw.githubusercontent.com/anikam13/ballhog-cv/main/docs/demo_tnc.gif)

## FrameShift

iPhone camera that recreates a reference photo with live on-device guides. No account, no backend.

[App Store](https://apps.apple.com/us/app/frameshift-camera/id6789638657) · [source](https://github.com/anikam13/frameshift)

## Balluptop

Browser NBA trivia: see the face, name the hooper.

Repo: [anikam13/balluptop](https://github.com/anikam13/balluptop)

Live URL in that README is [ballhog.app](https://ballhog.app). That host currently 404s (Railway), so treat the GitHub repo as the source of truth until it is back.

## FinLedger

[FinLedger](https://github.com/anikam13/finledger): local expenses/investments/income ledger with an MCP server and a rules-first reimbursement matcher. Public eval is a 22-example synthetic set (72.7% exact-set, 85.7% auto-match precision on that sample); the private ~92-example gold set is not published.

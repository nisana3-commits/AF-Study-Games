# AF Study Games

Bible-themed study games for the Amazing Facts Bible Study Guides, built for the
Skool communities of Dr. Nisana Miller, DVM.

## Trust Arcade

Six games built from Study Guide 1, "Is There Anything Left You Can Trust?"

| Game | Lesson content | Story |
|---|---|---|
| Angel of Light | Sixteen multiple-choice questions from sections 1 to 12 | Four veiled angels carry the answers; a heart reveals the true one white and the false ones black |
| Dry Ground | True and false statements from the summary sheet | Carry the ark across the parted Jordan (Joshua 3) |
| Dig Again the Wells | The seven archaeological confirmations of section 6, with dated discovery cards | Isaac reopens the wells the Philistines stopped (Genesis 26) |
| Road to Emmaus | Nine objections from sections 3, 4, 7, 9 and Your Questions Answered | Two travelers voice their doubts; answers warm the burning heart (Luke 24) |
| Of Whom Speaketh the Prophet | The twelve Messianic prophecies of section 9 | Philip runs to the scroll the Ethiopian is asking about (Acts 8) |
| The Way of Thy Commandments | True and false statements from the summary sheet | Run a lamp-lit path; true statements light lamps, false ones fall as stones (Psalm 119) |

Every game is drawn with Dr. Miller's own illustrations: the ark bearers and the
Canaan bank, Isaac, the well and the herdsman, the Emmaus road, Philip's desert,
and the lamp-lit cobbled path with a choice of runner. Cards on the menu are
labeled by the passage each game is set in.

The menu also carries a Scripture wall: every verse the lesson cites, grouped
under the lesson's own questions, with a hide-and-reveal mode for recall
practice. The page follows the device's light or dark setting, with a toggle.

On a phone the games show on-screen buttons; on a computer they show the keys
to use instead, and the play field is sized to fit the window.

## Verse wording

Wherever the study guide quotes a verse, the game uses the guide's wording (NKJV).
Verses the guide only cites by reference are shown in KJV and marked as such.
The discovery cards in Dig Again the Wells cite museum, university, and
Encyclopaedia Britannica pages by name.

## Hosting

The site is a single static file, `index.html`, with no build step. Import this
repository in Vercel or Netlify with the default settings and it deploys as is.
Scores are kept in the visitor's browser only.

## Updating

Edit `index.html` and push to `main`. The hosting provider rebuilds on every push.

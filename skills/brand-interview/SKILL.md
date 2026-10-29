---
name: brand-interview
description: Interviews a small-business owner in Hebrew, in small groups of questions, to build their brand kit: what they sell, who the ideal customer is, personality and voice, colors and fonts, competitors, goals. Produces BRAND.md, a pretty brand.html page, a brand.pdf and a short copy-paste prompt that other AI tools can use to write in the brand's voice. Use when the user says "brand kit", "ברנד קיט", "מיתוג", "בוא נבנה את המותג", "ראיון מותג" or /brand-interview.
---

# brand-interview

You run a brand interview with a business owner (a coach, therapist, consultant, local service: no design or marketing background) and turn the answers into a brand kit that other skills and AI tools can read.

Speak Hebrew, short and warm, no jargon. If you must use a term (מיצוב, טון), explain it in half a sentence. Address the user in the gender and number they use for themselves; if unknown, use plural neutral phrasing.

## Rules that never bend

- Never invent facts, claims, testimonials, numbers, licenses or results. Write only what the owner said or approved.
- Never write a promise of results (leads, revenue, cures, weight loss, "guaranteed"). In regulated fields (therapists, doctors, lawyers, financial advisors) ask what they may legally say and write it under "מה אסור להבטיח".
- Do not choose colors, fonts or a name on the owner's behalf without showing options and getting a yes.
- Never publish, send or upload anything. Files are written locally only.

## Before the first question

1. Check the working folder for an existing `BRAND.md`. If found, read it and ask whether to update it or start fresh.
2. Ask in one message: the business name, and links if any (website, Instagram, Google Business page, existing logo or brand files). If they give links, read them yourself and pre-fill what you can. Then only ask what is still unknown, and say what you already understood so they can correct it.

## How to interview

- Ask in small groups of 3 to 4 questions at a time, never a long list. Wait for the answers.
- If the owner does not know how to answer, do not skip. Explain why the question matters in one sentence, give a short example from a similar business, and offer 3 options to pick from. If they pick one, mark it as "הצעה שאושרה".
- If the owner answers vaguely ("שירות טוב"), ask once for a concrete example or a customer story.
- Keep a running list of open points. Come back to them at the end.

### Group 1: the business
- מה העסק מוכר, במשפט אחד פשוט? (מוצר או שירות)
- איך העסק מרוויח: סוג הלקוח, טווח מחירים, שירות חד-פעמי או מתמשך?
- מה מבדל אותך? למה לקוח יבחר בך ולא באחד אחר?
- הסיפור שלך: למה התחלת, מה הניע אותך, מה הניסיון שהביא אותך לכאן?

### Group 2: the ideal customer
- מי הלקוח האידיאלי: גיל, מגדר, מקצוע, איפה גר, מה הוא עושה ביום יום?
- מה הכאב שלו, מה מציק לו לפני שהוא מגיע אליך?
- איפה הוא נמצא: אינסטגרם, וואטסאפ, גוגל, המלצות מחברים?
- למה הוא מהסס? אילו שאלות והתנגדויות עולות לפני שהוא מחליט?

### Group 3: personality
- איך אתה רוצה שהלקוח ירגיש כשהוא פוגש אותך? שלוש מילים.
- אם המותג היה בן אדם: איך הוא מדבר, איך הוא לבוש, מה הוא לא היה אומר אף פעם?

### Group 4: the visual side
- יש כבר צבעים או לוגו? אילו צבעים אתה אוהב, ואילו לא מתאימים?
- יש גופנים שאתה משתמש בהם? אם לא: האם המראה צריך להיות קלאסי או מודרני, נקי או חם?
- If there is no palette yet, propose 3 palettes (HEX codes, with one line on the feeling of each) based on groups 2 and 3, and let the owner pick or mix. Check text/background contrast for readability (aim for at least 4.5:1) before presenting.
- If there are no fonts yet, propose 2 pairs of free Google Fonts that support Hebrew (for example Heebo, Assistant, Rubik, Secular One, Frank Ruhl Libre, Alef) and say what each feels like.

### Group 5: competitors
- מי המתחרים? שניים או שלושה עסקים דומים שהלקוח משווה אליהם.
- What makes this brand look or sound different from them? (Offer a suggestion from what you learned if the owner is unsure.)

### Group 6: voice and writing
- פונים בלשון יחיד או רבים (אתה/את או אתם), ובגוף ראשון יחיד או רבים (אני או אנחנו)?
- רמת רשמיות וסלנג: מדברים ישר ולעניין, חם וקליל, מקצועי ומאופק? יש הומור?
- Ask for 2 or 3 pieces of existing writing the owner is proud of (a post, a WhatsApp message, a bio). Read them and describe the voice you hear, then ask if it is right.
- Ask for words they love and words they never use.

### Group 7: goals and offer
- מה הפעולה שאתה רוצה מהלקוח: להשאיר טלפון, לקבוע פגישה, לקנות, לעקוב?
- מה ההצעה המרכזית שאתה רוצה למכור עכשיו?
- מה אסור להבטיח: מגבלות חוקיות או מקצועיות, ודברים שאתה פשוט לא רוצה להבטיח.

### Group 8: materials and channels
- איפה המותג מופיע: אינסטגרם, אתר, וואטסאפ, כרטיס ביקור, חולצות, שלטים?
- איזה לוגו וקבצים יש, ובאיזה פורמט? מי מצלם או מעצב עבורך?
- שם וסלוגן: האם השם סופי? Offer 3 slogan options in the owner's voice only if they ask for help, and never present a slogan as a promise of results.

## Confirm before writing

When all groups are done, show a short summary in Hebrew (about 15 lines): the business, the customer, the personality in 3 words, the voice rules, colors and fonts, the central offer, what must not be promised, and the open points. Ask: "זה נכון? מה לתקן?" Apply corrections. Write the files only after an explicit yes.

## Outputs

Write all four files to a `brand-kit` folder in the working directory.

1. **BRAND.md** (Hebrew, headings below, bullets not essays):
   - עסק (מה מוכרים, איך מרוויחים, מה מבדל, הסיפור)
   - קהל יעד (הלקוח האידיאלי, כאב, איפה נמצא, התנגדויות)
   - אישיות (3 מילים, המותג כבן אדם, מה הוא לא היה אומר)
   - טון דיבור (פנייה, רשמיות, מילים אהובות ואסורות, 3 דוגמאות כתיבה בקול המותג, 3 משפטים "לא ככה")
   - מתחרים והבידול
   - מראה (צבעים עם HEX ותפקיד של כל צבע, גופנים, סגנון תמונות, לוגו)
   - מטרות והצעה (הפעולה המבוקשת, ההצעה המרכזית, קריאה לפעולה)
   - מה אסור להבטיח
   - איפה המותג מופיע
   - נקודות פתוחות
   Mark every item the owner only accepted from your suggestion as `(הצעה שאושרה)`.
2. **brand.html**: one self-contained RTL page (inline CSS, Google Fonts link for the chosen fonts only) built from `brand-template.html` in this folder. Show the name and slogan, the colors as large swatches with HEX codes, the fonts with a sample line in Hebrew, the 3 personality words, voice dos and don'ts, and the central offer. Mobile friendly. Use the owner's own palette for the page.
3. **brand.pdf**: print `brand.html` to PDF with headless Chrome or Edge (`--headless --print-to-pdf`). If neither is installed, tell the owner to open `brand.html` and use "Print to PDF", and say the PDF was not created.
4. **brand-prompt.txt**: one short paragraph in Hebrew, ready to paste into any AI tool, that tells it who the business is, who the customer is, how to sound, which words to use and avoid, and what it must never promise. Under 150 words.

Finish by listing the four files with their paths, and say that other skills (carousels, captions, landing pages) can now read `BRAND.md`. Mention anything left open.

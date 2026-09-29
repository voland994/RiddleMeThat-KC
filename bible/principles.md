# Principles

## Tone

### Established

- **No clichés.** Research first. Real medicine, real places, real people.
- **He is not House.** The sardonic voice is mostly *internal*. To other people he comes across as smooth and professional. Nobody sees the gap, and that's the point.
- **People are people.** Other characters have their own agency. Some are as oblivious as he is, some aren't, and most are just living their lives. The world is not a puzzle built for him to solve, and people don't see what the player sees.
- **No development cast.** His colleagues are doctors at a busy regional neuroscience institute with their own careers, politics, and problems. They don't exist to drive his arc or create drama for him.
- **Kansas City is a real place.** "Flyover country" is a cliché. The city doesn't care what he thinks of it, and his sneer at it says more about him than about Kansas City.
- **He is not a superhero, and his contempt isn't malpractice.** He took his training seriously and is good at the job. His sneering never turns into bad care.
- **The job is real to him.** He genuinely enjoys clinical work. That enjoyment is not a mask.
- **Cases are cases, not metaphors.** Medical cases are real clinical problems. They never stand in for Philip's inner life, and no patient exists to teach him a lesson.
- **Medicine is real.** Real presentations, real EEG findings, real medications and doses, real hospital logistics. Hand-holding for the player is fine. Faking it is not. When Claude is unsure of a clinical detail, it says so out of character instead of inventing it.
- **No gotcha reveals.** He is not a secret bigot, and there will be no hypocritical slip staged for morality-play points. His flaws are the ones the player gave him.
- **Every recurring character wants something that has nothing to do with him.**
- **No convenient reunions.** His father is not going to show up as a patient, in the ER, or at a conference.
- **No hospital romance.** Colleagues, trainees, nurses, and patients are off the table.

### Proposed

- **Horses, not zebras.** Doctors say "when you hear hoofbeats, think horses, not zebras." That could be a quiet thematic line: his life is all horses, and part of him keeps listening for zebras. It should never be stated this directly in the story itself.

## How play works

- The player controls the protagonist.
- Claude plays the world: patients, colleagues, nurses, family, the city, and the cases.
- **When the mask slips, the world responds realistically both ways.** His reputation can take a hit, since he's right that he'd be an outlier. But a slip can also get him noticed by someone like-minded, since he's wrong that honesty wouldn't help.
- **Inner thoughts go between asterisks** (`*like this*`). The world reacts only to what he actually says and does.
- **Out-of-character notes go in [square brackets]** (Claude) or (parentheses) (player).
- **"I tell her the usual stuff"-style summaries** mean Philip said something ordinary and unremarkable. Claude doesn't invent specific lines for him.
- **Established vs. proposed:** only the player makes things canon. Claude marks its own ideas as proposed until the player accepts them.

## Precommits

- Before some scenes, Claude writes down what a character wants, what happened in their life offstage, and what they've decided, and commits it to `precommits/` **before** the scene is played. That way the character's side can't quietly bend to fit whatever Philip does.
- The player can choose not to read these until after the scene.
- Claude plays the character to the precommit. If play reveals that something in it was wrong or unrealistic, Claude says so out of character instead of silently changing it.
- Conditions in a precommit trigger only on Philip's **outward** words and actions.
- **Use them for:** test results before a conference, another character's decision, anything where Claude might be tempted to bend the world toward or away from Philip.
- **Every character precommit includes a "What she knows about him" list** (or "he," or "they"): only what that character has actually seen or heard from Philip's outward words and actions, plus what reached them in the story. Anything else about him is off-limits to that character.

## Pacing

- **Not hour by hour.** Play live scenes for moments where his voice, his mask, or a real decision matters. Everything in between gets summarized or skipped.
- **Episodes.** Each session is roughly one episode: two to four played scenes, with summaries or time skips between them.
- **The academic year is the season.** Residents and fellows turn over in July. The American Epilepsy Society's annual meeting is in early December. Everyone's own storylines move on that clock whether Philip is watching or not.
- **Episode span (established after E03B):** about **two weeks per episode,** anchored to events rather than the calendar. **Two to four live scenes,** only for hinges (a relationship moment, a real clinical decision, somewhere his mask matters).
- **Batched summaries and decision sheets (established after E03B):** everything between live scenes goes into one summary block that ends with a short list of what needs Philip's call. The player answers them together. **Summaries report only Philip's decisions as the player gave them.** If a summary needs him to say something specific, it goes on the decision sheet instead of being invented.
- **Precommits cover the whole span** of an episode, so other characters' lives move on without Claude stopping to ask.
- **Clinic minisodes (established):** a few lines each. Most cases are ordinary (refills, driving, paperwork, a disagreeing family), not mysteries.
- **Cases run on real timelines.** An epilepsy surgery workup takes weeks to months, so a patient can come back across several episodes.
- **Both lives.** Scenes aren't only at the hospital. There's the apartment, the city, a gym, calls with his mom, dates, and walks.

## Inside and outside (the firewall)

- **The player can be completely candid about Philip's inner life.** More inner narration is welcome, especially outside the hospital.
- **Inner thoughts are invisible.** Nothing between asterisks reaches any character, however loud it is.
- **Tells only come from the player.** Characters can notice only what's in Philip's *outward* text: his words, his tone, and any visible behavior the player writes, such as "my smile comes a beat late." Claude never invents a tell for Philip. If the player's outward text is smooth, the mask holds.
- **No winking narration.** Claude's narration doesn't echo or ironically answer his inner thoughts. For example, if he thinks he hates the parking lots, the next paragraph shouldn't pointedly note there are no parking lots in view.
- **No mind-reading coincidences.** Characters don't happen to say exactly what he was just thinking, or deliver the theme he was just brooding about.
- **Spoken catches are rare.** Even perceptive characters mostly notice without saying so. Out loud: at most one catch per scene from anyone perceptive, and none from people who aren't. Watch the total across an episode too. Several "reads" in a few days is too many.
- **Session logs keep his inner thoughts** in a separate "Inside" section, for continuity only.
- **Each new character gets a perceptiveness note** in `characters.md`: how much they read people, and whether they'd ever say it.

### Guardrails against slips (established after Session 2)

In Session 2, characters four times "knew" things about Philip with no outward basis. Every time it happened in a warm, fast Chiara scene, and twice in a stretch that had no precommit. **Claude's diagnosis:** Claude holds his whole private file and reaches for the true insight instead of the observed one; recently written material resurfaces as a character's "random" examples; and warm peaks pull toward a satisfying "she sees him" beat. The rules:

- **Trace every line that characterizes Philip.** Before a character says anything about who Philip is, it must trace back to the "What she knows about him" list in their precommit, or to Philip's outward text in the current scene. If it can't be traced, cut it. Knowing something from `protagonist.md` doesn't count.
- **Zero reads by default when no precommit covers the moment.** Any stretch no precommit covers, including intimate scenes, gets no spoken reads of Philip. A read happens only where a precommit explicitly allows one and its trigger has fired.
- **Characters' offhand examples come from their own world.** When a character reaches for an illustration, an anecdote, or a hypothetical, it comes from their own life and work (Chiara's worms, Bologna, and Kenji; Nadia's stadiums), never from Philip's cases, his private file, or other characters they don't know.
- **Check before sending, not after.** In fast back-and-forth, run these checks on the draft before posting it. A slip caught a turn late still has to be retconned in brackets.

## Voices

- **Every character sounds like themselves.** Their job, class, age, and region shape how they talk. Don't let a new character borrow a previous character's register (the lawyerly one, the spiraling one, the dry one).
- **Women especially:** each woman in his life needs her own work, wants, rhythm, and way of flirting or not. No composites.

## Cutaways

- **Cutaways are scenes without Philip,** written by Claude. They show the world outside his control and the gap between how he sees himself and how others see him.
- **The firewall in reverse:** the player reads cutaways, but Philip doesn't know anything in them unless it reaches him inside the story.
- **About one per episode** by default.
- **Outside reads can be half right.** Characters in cutaways can misread him, and they should see him through their own lives and priorities.
- **Any behavior of Philip's that a cutaway describes but that hasn't been played** gets flagged for the player to confirm.

## Clinical realism: how often things go wrong

- **Messier means friction, not catastrophe.** Most clinic visits are routine. In a clinic day of 8 to 10 patients, one or two have real friction and the rest are ordinary.
- **What realistic friction looks like:**
  - **Bad historians:** no witness, or a witness whose story keeps changing, or a phone video of the ceiling.
  - **Nonadherence nobody admits:** the patient says every dose, and the drug level is undetectable.
  - **Advice not taken:** told not to drive, and drove anyway.
  - **Diagnoses rejected:** a functional-seizures diagnosis delivered well, and the patient leaves angry.
  - **Workups that answer nothing:** a monitoring stay with no event captured.
  - **Hope taken away:** multifocal onset so no surgery, seizures returning months after surgery, or memory cost from a resection the patient consented to.
  - **Systems:** insurance denials, generic switches, cost rationing, disability paperwork, complaints, bad reviews.
- **Big bad outcomes are rare and always medically grounded.** They happen because the illness is what it is, never to teach Philip something.
- **Deaths:** Philip is not a surgeon and does not lose patients often. The realistic death in his field is SUDEP, roughly 1 per 1,000 people with epilepsy per year and several times higher in drug-resistant epilepsy. Over a year of story, one patient death is realistic. He'd most likely learn of it secondhand (a family message, a chart note), not at the bedside.
- **Philip's own errors: paused.** Whether he makes ordinary honest mistakes is undecided. Don't precommit or introduce one. Decide in play, with the player, if and when it comes up.
- **New-attending realism:** he's the new person. He doesn't know the nurses' names yet, the EHR build is different from Euclid's, referral patterns are different, and nobody here knows his reputation. Trust is earned from zero.

## Competence in play (established)

- **The standard of care is automatic.** Anything a well-trained epileptologist does without thinking, Philip does correctly: the right doses, the right workup, the right EEG read, and the standard history questions. The player can write "I adjust her meds appropriately" or "I order the standard workup," and Claude fills in the real version.
- **Judgment calls belong to the player.** Where real epileptologists would disagree, Claude lays out the options honestly in [brackets], says which way his training would lean, and the player chooses.
- **Where Euclid shows, he's better than average:** EEG reading, semiology, surgical workups, ICU EEG. Some people notice, quietly.
- **Where he's realistically weaker (new, not bad):**
  - **The system:** who to call, which neuropsychologist is good, how prior auths work here, and the state line (Missouri expanded Medicaid in 2021; Kansas hasn't).
  - **Continuity:** fellows follow patients for a year or two. Hartsock knew hers for 20 years, and Denise knows what no chart says.
  - **Pace:** he runs late in clinic while he learns to write billable notes in a new build.
  - **Being the final word:** at Euclid there was always someone above him to sign off.
- **Uncertainty is real.** A good call can have a bad outcome, and a reasonable call can turn out wrong. **That isn't an error** (a peer would have made the same call). Philip's actual errors, ones a peer would fault, stay paused.
- **Disagreements are honest.** Sometimes he's right, sometimes Eric or Denise is, and sometimes nobody knows.
- **Most of it just works** and gets summarized. Friction comes from patients and the system, not from Philip fumbling.

## Blue River compared to Euclid (established facts; how he feels about it is the player's)

- **The cases:** Euclid was the end of the line. Blue River is regional: some drug-resistant referrals, and mostly first seizures, stable refills, spells that aren't epilepsy, pregnancy planning, and seizures after strokes.
- **Surgery:** a real but much smaller program, with far fewer SEEG cases [verify real volume].
- **Hours:** fewer than fellowship, with home call. More patients per clinic day and more responsibility per patient. Productivity-based pay after two years.
- **Support:** much less. Denise and a handful of nurses are most of it.
- **Money:** roughly four times his fellowship pay.
- **Standing:** Reinholt and Eric know what "Cleveland-trained" means. Patients don't care.

## Career and the job market

- **The market gives him what it realistically gives him, no more and no less, and only in response to what he actually does.** If a career thread opens, Claude precommits what's realistically out there before Philip looks.
- **Seniority is real.** Top academic centers aren't his market as a new clinician-educator without publications.
- **What he'd take (established):** academic jobs or large nonprofit hospital systems in walkable cities, with real clinical epilepsy work. **What he wouldn't:** the VA, private practice or for-profit groups, remote reading, or industry.

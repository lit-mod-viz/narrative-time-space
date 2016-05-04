# Narrative Space/Time Expert Annotator Guidelines

## Goal

We would like to train a machine to discern boundaries between scenes in
novels.  Here, scenes are defined as discrete units of narrative time and
space. To provide the machine with instructive examples, we are asking a dozen
or so human volunteers to read a text and to mark **scene boundaries that are
indicated by changes in narrative time and space.**

## 1. Instructions

### 1.1 Markers

- To mark a change in time, use the symbol `@`.
- To mark a change in space, use the symbol `$`.
- To mark a simultaneous change in time and space, use either `@$` or `$@`.

**Markup can be done in-line within the plain text document sent by the
moderators.**

To ensure you document is in plain text please use the text editors included
in your operating system: *Notepad* for Windows and *TextWrangler* for
*TextEdit* for Mac.

When using *Notepad*: navigate to the `File` menu, select `Save As`. At the
bottom of the `Save As` dialog box, select `Plain text (*.txt)` from the `Save as
type...`  drop-down list.

When using *TextEdit*: navigate to the `Format` menu and select the `Make Plain
Text` option.

**To submit your results, save the completed file and attach it in
an email to the moderators.**

Markers should only be placed between two sentences. Insert a marker between
sentences A and B if sentence B begins in a new temporal or spatial location
from sentence A. In some cases, the sentence boundary conceals an implicit
"jump" from one location to the next. In other cases, sentence A may function
as a fluid transition out of the previous location, and B may be a transition
into the new one.

We would like you to trust your gut when identifying significant changes in
time and space. However, when you encounter a highly ambiguous situation or
one that is not covered in this document, note your uncertainty by appending a
question mark to the usual symbol (`@?`, `@?`, `@$?`, `$@?`).

### 1.2 Timeline and Contact Information

#### 1.2.1 Pilot

We are running a short "pilot" task to garner feedback on the clarity of the
annotation guidelines and to get an initial sense of inter-annotator
agreement. The pilot consists of a single chapter of text, which will be sent
out to all annotators.  Please complete your annotations in-line within the
plain text file, and submit by attaching the modified file in an email to the
moderators.

#### 1.2.2 Due dates

| date      | task                                                    |
|-----------|---------------------------------------------------------|
| May 12th  | complete pilot and submit to moderators.                |
| June 5th  | complete full novel and submit to moderators.           |

Please let us know as soon as possible if you require an extension.

#### 1.2.3 Moderators

Melody Ju, melody@cs.columbia.edu  
Dennis Tenen, dt2406@columbia.edu  
Nicholas Dames, nd122@columbia.edu  

## 2. Definitions

### 2.1 Narrative (diegetic) worlds

Narrative time and space differs from that of the reader. A few minutes in the
reader's world may constitute decades in the fictional one. Time may not
be continuous, and events may be presented out of order. The same
goes for space - a novel's protagonist may understand the story
from a different vantage point than that of the narrator.
To complicate matters, fictional stories often contain multiple layers of narrative---worlds
within worlds---which unfold simultaneously in multiple dimensions. 

### 2.2 Time changes

You may think of a time change as a disruption in the assumed,
smooth, linear progression of time - a tear, gap or other incongruity.  

Look for evocations of time that situate scenes or events 
at points or spans on the narrative timeline. A temporal marker may establish an absolute
or relative point in time ("May 5th," "a few days later"), symbolically 
position an event in time ("the first time X happened," "before X...now Y"), 
or circumscribe an event's duration. All markers may be precise or vague, and
operate on varying levels of time granularity, from seconds to decades. 

Note that not all time changes correspond to a change in scene. You 
must distinguish between when time is used to mark a scene change, and
when it indicates something else.

**Example A**

> It was evident, indeed, that she wished me to drop the subject, which I did accordingly. **@** 
 
> For several subsequent days I saw little of Mr. Rochester. In the mornings he seemed much engaged with business, and, in the afternoon, gentlemen from Millcote or the neighbourhood called, and sometimes stayed to dine with him.  When his sprain was well enough to admit of horse exercise, he rode out a good deal; probably to return these visits, as he generally did not come back till late at night. During this interval, even Adèle was seldom sent for to his presence, and all my acquaintance with him was confined to an occasional rencontre in the hall, on the stairs, or in the gallery, when he would sometimes pass me haughtily and coldly, just acknowledging my presence by a distant nod or a cool glance, and sometimes bow and smile with gentlemanlike affability. 

Explanation: Although time is marked several times (in the mornings...
in the afternoon), the only scene change is inserted before the phrase 
"for several subsequent days." This marks a transition to a cohesive
period of time characterized by Mr. Rochester's preoccupation with 
various things besides the narrator's companionship. Although the pace
of the narrative has quickened, taking on the effect of summary, and
several events that occur at different times are described, the 
repetition of these events are bounded by the duration of the entire
time period.
 
**Example B**

> A long grace was said and a hymn sung; then a servant brought in some tea for the teachers, and *the meal began*. **@**

> Ravenous, and now very faint, I devoured a spoonful or two of my portion without thinking of its taste.

Explanation: Here, time is more metaphorical, emerging from
the commencement of the meal - "lunchtime" has begun.  
 
**Example C**

> "But I have studied the place for myself," continued Mr. Enfield.
"It seems scarcely a house. There is no other door, and nobody goes
in or out of that one but, once in a great while, the gentleman of
my adventure. There are three windows looking on the court on the
first floor; none below; the windows are always shut but they're
clean. And then there is a chimney which is generally smoking; so
somebody must live there. And yet it's not so sure; for the
buildings are so packed together about that court, that it's hard to
say where one ends and another begins."

> *The pair walked on again for a while in silence;* and then,
"Enfield," said Mr. Utterson, "that's a good rule of yours."

Explanation: The passage of time is evoked, but it only serves to
indicate that both characters were lost in thought. After the temporal
signal, the two are still walking along the same path, 
engaged in the same conversation. No scene change has occurred. 

### 2.3 Space changes

While spaces in a novel can be hierarchically organized by relations of 
containment (with rooms or streets always occurring within more
general settings such as houses or cities), we are interested in the *specific
and dynamic* over the general and static. Pay attention to the constantly shifting 
spatial frames that capture the immediate surroundings of events - the 
props and backdrops that potentiate characters' thoughts and actions 
from scene to scene. 

Strong indicators of significant spatial change may include partitions and pathways 
between spaces (walls, hallways, doors, windows), and actions of crossing 
thresholds.

A change in space may be abrupt (cinematically speaking, when a shot "cuts"
to a new setting). Or it may be continuous, simulating embodied travel (camera follows 
character from kitchen to backyard).

Changes in space may occur when narrative perspective jumps from one character
to another, depending on the surroundings of each character.  

Not all changes in space correspond to a change in scene. 

**Example D**

> "No; you are less than a servant, for you do nothing for your keep. There, sit down, and think over your wickedness." **$**

> They had got me by this time into the apartment indicated by Mrs. Reed, and had thrust me upon a stool: my impulse was to rise from it like a spring; their two pair of hands arrested me instantly.

**Example E**

> I had put on some clothes, though horror shook all my limbs; I issued from my apartment. **$** 

> The sleepers were all aroused: ejaculations, terrified murmurs sounded in every room; door after door unclosed; one looked out and another looked out; the gallery filled.  Gentlemen and ladies alike had quitted their beds; and “Oh! what is it?”—“Who is hurt?”—“What has happened?”—“Fetch a light!”—“Is it fire?”—“Are there robbers?”—“Where shall we run?” was demanded confusedly on all hands.

### 2.4 Suspending narrative, breaching narrative levels

When a character narrates an eventful story situated in another time/space, 
breaching narrative levels, a scene change may occur. Consider whether
the embedded story immersively transports the reader to another time or place, or 
whether the story/memory is merely referenced. 
What if the thing we jump to is not eventful?
When a narrator suspends the event-story to make room for static descriptions
or summary, this may also be a scene change, depending on whether some differentiated
time or space is described in such a way that it takes on flesh in the reader's mind.


**Example F**

> Mr. Rochester did, on a future occasion, explain it.  It was one afternoon, when he chanced to meet me and Adèle in the grounds: and while she played with Pilot and her shuttlecock, he asked me to walk up and down a long beech avenue within sight of her.

> He then said that she was the daughter of a French opera-dancer, Céline Varens, towards whom he had once cherished what he called a “grande passion.”  This passion Céline had professed to return with even superior ardour.  He thought himself her idol, ugly as he was: he believed, as he said, that she preferred his “taille d’athlète” to the elegance of the Apollo Belvidere. **@$**

> “And, Miss Eyre, so much was I flattered by this preference of the Gallic sylph for her British gnome, that I installed her in an hotel; gave her a complete establishment of servants, a carriage, cashmeres, diamonds, dentelles, &c.  In short, I began the process of ruining myself in the received style, like any other spoony.  I had not, it seems, the originality to chalk out a new road to shame and destruction, but trode the old track with stupid exactness not to deviate an inch from the beaten centre.  I had—as I deserved to have—the fate of all other spoonies.  Happening to call one evening when Céline did not expect me, I found her out; but it was a warm night, and I was tired with strolling through Paris, so I sat down in her boudoir; happy to breathe the air consecrated so lately by her presence.  No,—I exaggerate; I never thought there was any consecrating virtue about her: it was rather a sort of pastille perfume she had left; a scent of musk and amber, than an odour of sanctity.  I was just beginning to stifle with the fumes of conservatory flowers and sprinkled essences, when I bethought myself to open the window and step out on to the balcony.  It was moonlight and gaslight besides, and very still and serene.  The balcony was furnished with a chair or two; I sat down, and took out a cigar,—I will take one now, if you will excuse me.”

Explanation: Mr. Rochester begins telling a story that immerses the reader in another time and place. Although he refers to the past in the second paragraph, it is a mere reference to a memory. That memory becomes a scene of its own when he launches into detailed description and vignette in the third paragraph, transporting the reader to the past. 

**Example G**

> “What do you want?” I asked, with awkward diffidence.

> “Say, ‘What do you want, Master Reed?’” was the answer.  “I want you to come here;” and seating himself in an arm-chair, he intimated by a gesture that I was to approach and stand before him.

> John Reed was a schoolboy of fourteen years old; four years older than I, for I was but ten: large and stout for his age, with a dingy and unwholesome skin; thick lineaments in a spacious visage, heavy limbs and large extremities.  He gorged himself habitually at table, which made him bilious, and gave him a dim and bleared eye and flabby cheeks.  He ought now to have been at school; but his mama had taken him home for a month or two, “on account of his delicate health.”  Mr. Miles, the master, affirmed that he would do very well if he had fewer cakes and sweetmeats sent him from home; but the mother’s heart turned from an opinion so harsh, and inclined rather to the more refined idea that John’s sallowness was owing to over-application and, perhaps, to pining after home.

> John had not much affection for his mother and sisters, and an antipathy to me.  He bullied and punished me; not two or three times in the week, nor once or twice in the day, but continually: every nerve I had feared him, and every morsel of flesh in my bones shrank when he came near.  There were moments when I was bewildered by the terror he inspired, because I had no appeal whatever against either his menaces or his inflictions; the servants did not like to offend their young master by taking my part against him, and Mrs. Reed was blind and deaf on the subject: she never saw him strike or heard him abuse me, though he did both now and then in her very presence, more frequently, however, behind her back.

Explanation: Although the narrator suspends the story to provide extended static description, no scene change occurs. The description is not anchored in another time and place. 

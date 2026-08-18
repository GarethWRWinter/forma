# The Founding Hundred Letters

Waitlist nurture sequence. One a week from joining until the doors open on
15 September, and every one leaves the reader measurably faster before they have
paid anything. Reciprocity is the strategy, not a nice-to-have. Founder voice,
signed G, sent from gareth@ridewithforma.com.

All of them go by hand. Letter 0 is the only one the app sends, and it fires on
joining. After each manual send, mark it off:

    railway run --service Postgres bash -c \
      'DATABASE_URL="$DATABASE_PUBLIC_URL" .venv/bin/python \
       scripts/mark_letters_sent.py --before YYYY-MM-DD --commit'

The run-in, weekly on a Tuesday:

| When         | What                                    |
| ------------ | --------------------------------------- |
| Tue 18 Aug   | The re-introduction, to the first 18     |
| Tue 25 Aug   | Letter 1, the bottle                     |
| Tue 1 Sept   | Letter 2, Sa Calobra                     |
| Tue 8 Sept   | Letter 3, light and powerless            |
| Mon 14 Sept  | Letter 4, the free ten watts             |
| Tue 15 Sept  | Doors open                               |

The order is load-bearing. Letter 1 says doing beats knowing, Letter 2 says a bad
day is data rather than a verdict, Letter 3 says aim at the right thing, and
Letter 4 hands over free speed on the way through the door.

---

## Letter 0 · Your place is held (sent on joining)

**Subject: your place is held**

This one is not drafted here. It lives in `app/services/email_service.py` as
`send_waitlist_welcome`, because the app sends it automatically and the code is
the only version that can be true. Two variants sit beside it there:
`send_waitlist_reintroduction`, for the eighteen who joined through the old
sheet and then heard nothing for six weeks.

What it does, and why, in case it ever needs rewriting:

Compassionate Curiosity, in order. It acknowledges before it asks, naming the
thing the rider probably feels and has not said: that the last plan came apart
and the weak link was them. It says it was not. Then one open question, what
frustrates you most about your training right now, with three prompts under it
as scaffolding rather than homework, and a line saying out loud that one sentence
is a complete answer.

It is a reply, never a form. A form is a company collecting. A reply is a person
listening, and reading every one is the whole promise.

It teases Letter 1, so if the sequence is ever reordered, that line has to move
with it.

---

## Letter 1 · The bottle (why doing beats knowing)

**Subject options:**
1. the day I nearly took out Bradley Wiggins
2. Watching is not training
3. ten thousand bottle handouts, zero skill

*Recommended: 1. The story earns the click and the body cashes it.*

I had watched more Tour de France bottle handouts than almost anyone alive. Decades
of them, from the sofa and then from inside the sport. So when Bradley Wiggins
dropped back to the team car at the Tour of Britain and I was the one holding the
bottle, I knew exactly what to do.

I held it perfectly. Then, at the last second, I doubted myself, flipped my hand,
and very nearly put a bidon into the front wheel of Britain's first Tour winner.

The lesson cost me a heartbeat and taught me everything: no matter how many times
you have watched something, you cannot integrate it until you practise it. Knowing
is not skill. Watching is not training. Reading this letter is not riding.

Which is the politest way I can say: whatever plan you follow, mine or anyone's,
the magic is not in the plan. It's in the doing, repeated, on the days it's
inconvenient. The system's job is to make the doing so clear and so fitted to your
life that the excuses run out.

That's what I've spent two years building, and it opens on 15 September.

G

PS. Next week: the climb that beat me twice in the same week, and what the two
failures taught me that the ride which went well never could.

---

## Letter 2 · Two failures and seven seconds (the head)

**Subject options:**
1. two failures and seven seconds
2. the ride that taught me nothing
3. I climbed Sa Calobra three times in one week

*Recommended: 1. The arithmetic is odd enough to open.*

Sa Calobra is 9.44 kilometres at seven per cent, twenty six bends, and no
interest whatsoever in how your winter went. I wanted to go under thirty minutes.
Not because thirty means anything physiologically, it doesn't, but because it's
the sort of round number a bloke with a job and a kid can hold onto through a
British winter.

Monday I didn't finish. Six kilometres in, my seatpost twisted and I rolled back
down. I'd torqued it properly the night before on my kitchen floor, feeling like
a team mechanic. What I'd never done was test it under half an hour of
out-of-the-saddle load on a seven per cent gradient.

Tuesday was the one that actually hurt, because there was nobody to blame.
30:47. I'd gone out to hold 340 watts and averaged 325.

That evening I didn't go for a consoling beer and decide I needed a bigger
engine. I opened the file. It takes ten minutes and it's the most useful habit in
this whole story.

The power trace looked like a bread knife. Dozens of small collapses in it, and
every single one a gear change. Twenty six bends, a gradient that never settles,
and I'd been chasing a comfortable cadence the whole way up. Each shift cost a
fraction of a second of load. Invisible on its own. Over half an hour they were
most of my deficit.

Friday: 29:53. Seven seconds inside the target that had beaten me twice.

I needed fifty four seconds and nobody gets fitter in three days. It came from
letting the cadence wander between 75 and 105 instead of defending 95, pacing
against the clock instead of against my own opinion of how hard it felt, and a
handful of free seconds from a lighter helmet and a caffeine gel taken when it
would actually do something.

So, this week's usable bit. The next time a ride disappoints you, don't ride it
off and don't harden up. Open the file. Ten minutes, looking for where the power
goes flat and what you were doing at that exact moment. Most plateaus are not one
big fault. They're a hundred small leaks, and you cannot see a single one of them
from the saddle.

The two failures did all the coaching. The 29:53 was just the bit you put on
Strava.

G

PS. Most of us treat a bad day as a verdict on ourselves. It's data. The
distance between those two sentences is most of a season.

---

## Letter 3 · Light and powerless (the wrong goal)

**Subject options:**
1. I became light and powerless simultaneously
2. The year I chased the wrong number perfectly
3. what a season of mistakes taught me about goals

*Recommended: 1. It's the canon line, and it's irresistible.*

In 2019 I decided the answer was weight. World tour riders hold big watts at 60-odd
kilos, so I chased the ratio from the wrong end: I got light.

It worked, in the sense that the scale said what I wanted. And I became light and
powerless simultaneously. The watts left with the kilos. It took a year to rebuild,
and the rebuild only started when I stopped asking "what do the pros weigh?" and
started asking "what kind of rider am I?"

The answer, it turns out: a rouleur. A diesel. The last one standing at the end of a
long day. Once I trained the rider I am instead of the rider on the poster, the
numbers moved for the first time in two seasons.

This week's usable bit: write one sentence that describes the rider you actually
are. Not aspiration, description. Where do you finish strong? What do clubmates ask
you to do? Train that for a month and watch what happens to your morale, which is a
performance metric, whatever the apps say.

G

PS. The wrong goal pursued perfectly is still the wrong goal.

---

## Letter 4 · The free ten watts (marginal gains)

**Subject options:**
1. the gains that cost nothing
2. Wax, pressure, and the wind you didn't check
3. What Team Sky taught me that fits in a kitchen

*Recommended: 2. Concrete trio, mild curiosity.*

A decade around Team Sky taught me that marginal gains was never really about the
wind tunnel. The expensive stuff got the headlines. The compounding stuff was almost
free.

Three you can bank this week:

Wax your chain. A clean waxed chain saves real watts over a dirty oiled one and
your drivetrain lives years longer. Wax over oil, always. This is doctrine, and one
day your cassette will thank you in savings.

Check your pressure against your actual weight and tyre width, not the number your
clubmate runs. Most riders are over-inflated and slower for it, bouncing instead of
rolling.

Read the wind before you ride, not during. Two minutes with a forecast turns "that
was a horrible headwind" into "I did my efforts with the tailwind and sat in coming
home." Same legs, better ride.

Compound improvements. Invisible in isolation. Significant over time. That sentence
is doing a lot of work in my life, and it built the app you're waiting for.

Which brings us to the end of the run-in. Five letters ago you were a name on a
list. I hope you're a few watts better off than you were, because that was the
deal and it cost you nothing.

The doors open tomorrow. There are a hundred places and you've been holding one
of them since the day you joined.

G

PS. Everything in these five letters is in the app, doing itself. The wind read
before you roll out, the file opened for you after a disappointing ride, the plan
that bends when your week does. Tomorrow you stop doing it by hand.

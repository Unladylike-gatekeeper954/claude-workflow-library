# Study Workflow

> Turn any subject into organized notes, flashcards, and 
> practice tests — step by step.

---

## Who Is This For?

- Students preparing for exams
- Self-learners picking up a new subject
- Anyone who wants to study smarter, not harder

## What You'll Have at the End

- A clear breakdown of everything you need to learn
- Simple, organized notes for each topic
- Flashcards you can review anytime
- Practice questions with answers
- A day-by-day study schedule

---

## The Workflow

### Step 1 — Map Out What You Need to Learn

Before studying, you need to see the full picture. This 
step gives you a complete list of everything to cover.

**Prompt:**

    Role: You are an expert tutor who has helped hundreds of 
    students master [SUBJECT] — you know exactly what matters, 
    what gets tested, and what beginners consistently overlook.

    Objective: Break down everything I need to learn about 
    [SUBJECT] into a clear, organized list — from basics 
    to advanced topics.

    Context:
    - I'm studying for: [WHAT — exam name, certification, 
      personal goal]
    - My current level: [beginner / intermediate / advanced]
    - My deadline: [DATE or "no deadline"]
    - I struggle most with: [TOPIC or "nothing specific yet"]

    Output: A numbered list of all subtopics I need to study, 
    organized from foundational to advanced. For each subtopic, 
    add one line explaining why it matters.

    Rules:
    - Do not include topics beyond what's relevant to my 
      stated goal
    - If my deadline is very short, flag which topics are 
      highest priority and which can be skipped
    - Be honest if the scope is too large for my timeline
    - Organize strictly from foundational to advanced — 
      do not mix levels

**After you get the response, ask:**

    What important subtopics are missing from this list that 
    could appear on an exam or that beginners often overlook?

---

### Step 2 — Get Clear Notes on Each Topic

Go through each subtopic one at a time. Understand it 
fully before moving to the next.

**Prompt:**

    Role: You are a patient tutor who explains things in 
    plain, everyday language — you never move on until 
    the student genuinely understands, not just nods along.

    Objective: Teach me [SUBTOPIC] so I understand it well 
    enough to explain it to someone else.

    Context:
    - This is part of my study plan for [SUBJECT]
    - My level: [beginner / intermediate / advanced]
    - I learn best through: [examples / analogies / 
      step-by-step explanations — pick one]

    Output:
    1. A simple definition (1-2 sentences, no jargon)
    2. Why it matters (how it connects to the bigger subject)
    3. A real-world example I can relate to
    4. The most common mistake people make about this topic
    Keep it under 300 words.

    Rules:
    - Never use a technical term without immediately 
      defining it in plain language
    - If I say "simpler," drop one full level in complexity
    - Connect every explanation to something I already 
      know or use in daily life
    - If this topic requires understanding a prerequisite 
      I haven't mentioned, flag it before explaining

**Helpful follow-ups:**
- Can you explain that like I'm 10 years old?
- Give me another example from everyday life.
- What's the most common exam question about this topic?

---

### Step 3 — Make Flashcards

Flashcards force your brain to recall information — 
which is how you actually remember things long-term.

**Prompt:**

    Role: You are a flashcard expert who creates cards that 
    test real understanding and application — not cards that 
    can be answered by pattern recognition alone.

    Objective: Create flashcards for [SUBTOPIC] that help 
    me remember and apply what I learned.

    Context:
    - I just studied [SUBTOPIC] as part of [SUBJECT]
    - My exam/goal is: [WHAT]
    - I want a mix of easy and challenging questions

    Output: 15 flashcards in this exact format:

    Card 1
    Q: [question]
    A: [concise answer — max 2 sentences]

    Mix:
    - 5 definition cards (What is...?)
    - 5 understanding cards (Why does...? How does...?)
    - 5 application cards (What would happen if...?)

    Rules:
    - No card should be answerable by guessing from 
      the question alone
    - Application cards must require genuine thinking, 
      not just recall
    - If a concept is commonly confused with another, 
      create a card that tests the distinction
    - Keep answers concise — if an answer needs more than 
      2 sentences, the question is too broad

---

### Step 4 — Test Yourself with Practice Questions

Reading notes feels productive but doesn't build real 
knowledge. Testing yourself does.

**Prompt:**

    Role: You are a professor writing a fair but rigorous 
    practice exam — you test genuine understanding, not 
    memorization of facts that won't transfer to real 
    application.

    Objective: Create a practice test for [SUBJECT/SUBTOPIC] 
    that covers all the important points.

    Context:
    - This is for: [EXAM NAME / self-assessment]
    - Difficulty: [match my actual exam / slightly harder / 
      beginner friendly]
    - Topics to cover: [LIST SUBTOPICS or "everything 
      we've discussed"]

    Output:
    - 10 multiple choice questions (4 options, one correct)
    - 5 short answer questions (2-3 sentence answers)
    - 2 essay questions (for deeper thinking)

    Put all answers and explanations in a separate section 
    at the very end labeled "ANSWER KEY." For each answer, 
    briefly explain why it's correct.

    Rules:
    - Multiple choice distractors must be plausible — 
      not obviously wrong
    - Short answer questions must require explanation, 
      not just a recalled fact
    - Essay questions must require synthesis of multiple 
      concepts, not a single definition
    - The answer key must explain why wrong answers 
      are wrong, not just state the correct one

**After completing the test, ask:**

    I got these wrong: [LIST QUESTIONS YOU MISSED].
    Explain each one simply and give me a memory trick 
    to remember the correct answer.

---

### Step 5 — Build Your Study Schedule

A plan you follow beats random studying every time.

**Prompt:**

    Role: You are a study coach who specializes in efficient 
    learning and spaced repetition — you build schedules 
    people actually follow, not ideal schedules that collapse 
    after day two.

    Objective: Create a realistic study schedule I can 
    actually stick to.

    Context:
    - Subject: [SUBJECT]
    - Days until exam/deadline: [NUMBER]
    - Hours I can study per day: [NUMBER]
    - Topics to cover: [LIST FROM STEP 1]
    - My weak areas: [TOPICS I STRUGGLED WITH]

    Output: A day-by-day schedule as a simple table:

    | Day | Topic | Activities | Time |

    Include:
    - Which topic to study each day
    - Time split between reading, flashcards, and 
      practice tests
    - Built-in review days (revisit older material)
    - One rest day per week
    - A final review day before the exam

    Rules:
    - Be realistic about daily hours — do not schedule 
      more than I said I can commit
    - Weak areas must get more time than strong areas
    - Space repetition properly — do not cluster all 
      review of one topic in a single day
    - If my timeline is too short to cover everything, 
      tell me which topics to prioritize and which to 
      cut or skim

---

## Pro Tips

- Do one step fully before moving to the next. Don't 
  make flashcards before you understand the notes.
- Talk back to Claude. If an explanation is confusing, 
  say "That didn't make sense. Try explaining it differently."
- Study in short blocks. 25 minutes of focused study 
  plus a 5-minute break beats 3 hours of unfocused reading.
- Review flashcards the same day you make them. Your 
  memory is strongest right after learning something new.
- Redo practice tests after a few days. If you still 
  get the same questions wrong, that's exactly where to focus.

---

## Common Mistakes

| Mistake | Why It Hurts You | Do This Instead |
|---------|-----------------|-----------------|
| Not stating your level | AI gives explanations too easy or too hard | Always say beginner, intermediate, or advanced |
| Studying everything at once | Nothing sticks when you rush | One subtopic at a time, fully understood |
| Only reading notes | Passive learning equals weak memory | Use flashcards and practice tests actively |
| Skipping the schedule | No structure equals procrastination | Build the schedule in Step 5 and follow it |
| Accepting confusing answers | You move forward without understanding | Ask "explain it simpler" or "give me an example" |

---

## Quick Start

Don't have time to read everything? Start here:

1. Do Step 1 to see what you need to learn
2. Do Step 2 for your weakest topic
3. Do Step 3 to make flashcards for that topic
4. Repeat Steps 2-3 for each topic
5. Do Step 4 when you've covered everything
6. Do Step 5 to plan your remaining time

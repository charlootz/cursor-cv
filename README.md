# cursor-cv – a resume feedback tool built for cursor

a repeatable way to tighten your resume with help from ai.  
keep every edit, measure what works, and hit send with confidence.

> **tl;dr**: drop your resume in here, paste the job postings, create a conversation in cursor, act on the feedback, commit the change. repeat.

<img width="1920" alt="image" src="https://github.com/user-attachments/assets/903542c2-50b1-428c-b704-a6194d2e0120" />

---

## why bother?

* **fresh eyes on demand** – let an ai assistant point out blind spots any time, in minutes  
* **version history** – every tweak lives in git, so you can roll back or compare  
* **job-aware** – tailor one resume per role instead of flooding a single doc with keywords  
* **learning loop** – log what you tried and what moved the needle for next time

---

## repo tour

```
cursor-cv/
├── README.md                    # you are here
├── instructions.md              # the prompt that makes the magic happen
├── about-candidate-log.md       # your career story + discoveries
├── resume-template.md           # starter template (optional)
├── resume.md                    # your actual resume
├── example/                     # see it in action with sarah chen
├── feedback/
│   ├── template.md             # review structure
│   ├── implementation.md       # track what you did
│   └── reviews/                # ai feedback goes here
├── job-descriptions/           # target roles (key to specific feedback!)
└── resume-versions/            # your resume evolution
    └── v1-baseline-[date].md
```

---

## quick start

1. **clone**
   ```bash
   git clone https://github.com/yourusername/cursor-cv.git
   cd cursor-cv
   ```

2. **drop your stuff in**
   - copy `resume-template.md` → `resume.md` (or just paste your .md resume)
   - add job posts inside `job-descriptions/[company-role].md` (this is crucial!)

3. **fire off the prompt**
   - open `instructions.md`, follow the steps in your ai tool of choice
   - the ai will analyze your resume against the specific job description
   - save the ai's response to `feedback/reviews/[role]-[date].md`

4. **ship improvements**
   - tick items in `feedback/implementation.md`
   - commit changes with a msg like `feat: quantify impact at startup (solutions-eng role)`
   - copy `resume.md` to `resume-versions/` before big edits

5. **loop**  
   rinse & repeat for every application. watch your resume level-up over time.

---

## the job-descriptions magic

dropping job descriptions in `job-descriptions/` unlocks:
- **keyword gap analysis** – see exactly what's missing for this role
- **targeted rewrites** – get specific bullet point suggestions that match the job
- **follow-up questions** – ai asks clarifying questions to help you nail the details
- **priority fixes** – know what to change first based on the specific role

example flow:
```
you: "review my resume against the openai pm role"
ai: "you're missing search/IR experience. do you have any projects with search?"
you: "actually yes, i built search for our api docs"
ai: "perfect! here's how to reframe that experience..."
```

---

## best practices

* **name versions well**  
  `v3-data-focus-2024-01-20.md` beats `final_FINAL.md`

* **one change at a time**  
  easier to see what works

* **ask specific questions**  
  the sharper the prompt, the sharper the feedback

* **add multiple job descriptions**  
  see patterns across similar roles

---

## example

check out `example/` to see sarah chen go from generic pm resume to openai-ready in one review cycle:


## license

MIT

---

**remember**: ai is your helper, not your ghostwriter. keep your voice, own your story, and hit send.

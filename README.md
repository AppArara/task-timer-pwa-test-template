# Task Timer PWA - Coding Test

Welcome! You've been invited to complete a coding test for a part-time junior developer position.

## ⚠️ IMPORTANT: First-Time GitHub Classroom Users

**If you're seeing a "Repository Access Issue" error:**

1. **Check your email inbox** - GitHub Classroom sent you an invitation email
2. **Check spam/trash folders** if you don't see it
3. **Click the "View Invitation" button** in the email
4. **Click "Accept this assignment"** on the GitHub Classroom page
5. **Wait 10-30 seconds** for your personal repository to be created
6. **Refresh this page** - you should now see the files below

**Still having issues?** Email Dan with a screenshot of the error.

---

## 🔔 What to Expect When You First Open Your Repository

**You'll see some automatic commits from GitHub Classroom - this is normal!**

- "Initial commit" - Your starter code
- "add online IDE url; add deadline" - Classroom metadata (you can ignore)
- "GitHub Classroom Feedback" - Creates feedback system for code review

**You'll also see warnings:**

1. **"Your main branch isn't protected"** - Click "Dismiss". You NEED to push to main for this test.
2. **"This branch is 3 commits ahead"** - This is normal. GitHub Classroom added those commits automatically.

**How to see your auto-grading score:**

Every time you push code, GitHub Actions automatically grades your submission:

1. Go to the **"Actions"** tab at the top of this repository page
2. You'll see a list of workflow runs - click on the **latest one** (top of the list)
3. Wait 1-2 minutes for the workflow to complete:
   - **Green checkmark ✅** = Passed (score ≥ 30 points)
   - **Red X ❌** = Failed (score < 30 points, or code has errors)

4. **To see your score breakdown:**
   - Click on the workflow run title to open it
   - Scroll down to the **"grade summary"** section (about halfway down)
   - You'll see a table showing your points for each requirement
   - Example:
     ```
     ⚠️ Needs Work Score: 20/110 points
     
     | Criteria | Points | Status |
     | Personal Answers | 10/10 | ✅ |
     | Tests Exist | 0/10 | ❌ |
     | Component Renders | 0/15 | ❌ |
     ```

5. **If your score is below 30 points (workflow fails):**
   - Click on the red "grade" job in the left sidebar
   - Expand the **"Fail if score too low"** step at the bottom
   - You'll see a **detailed explanation** of exactly what's missing:
     ```
     ❌ SCORE TOO LOW: 20/110 points (minimum 30 required)
     
     Your submission is incomplete. Here's what's missing:
     
     ❌ Tests Exist (0/10 points)
        → src/components/FocusTimer.test.tsx not found
        → You need to write tests for your component
     
     ❌ Component Renders (0/15 points)
        → src/components/FocusTimer.tsx not found
        → Create the FocusTimer component and export it
     ```

**Pro tips:**
- Push early and often to see your score improve
- The grader runs on every push - use it to check your progress
- The score summary shows at the bottom of each workflow run
- If the workflow fails, read the error message carefully - it tells you exactly what to fix

---

## What This Is

Task Timer PWA is a simple productivity app created by Dan Donahue as a quick coding experiment. It helps people track tasks and stay focused. Your job is to add a new "Focus Timer" feature following the production manual.

## Your Mission

Add a focus timer feature that helps users stay on task with countdown alerts. You'll work through 5 chapters in the production manual, building the feature step-by-step.

## Getting Started

1. **Read the manual first**: Open `MANUAL.md` and read all 5 chapters
2. **Answer personal questions**: Fill out `CANDIDATE_ANSWERS.md` 
3. **Set up your environment**: Follow Chapter 1 instructions
4. **Build the feature**: Work through Chapters 2-4
5. **Submit**: Follow Chapter 5 to submit your work

## Timeline

- **Deadline**: 7 days from the day after you receive the invitation email
- **Reminder**: You'll get an auto-reminder on Day 5
- **Auto-close**: Submissions close automatically on Day 8

## What We're Looking For

- Can you follow detailed technical instructions?
- Do you catch obvious mistakes and use good judgment?
- Can you write tests (bonus points if you write tests FIRST)?
- Do you communicate clearly in your answers?
- Can you ship working code on time?

## Important Notes

- This is a **real coding test** - your submission will be auto-graded
- Work on **your local machine** in VS Code (not cloud IDEs)
- The starter app is already built - you just add the focus timer
- Ask Dan if you're truly stuck (but try to figure it out first!)

## Getting Help

If you hit a wall:
1. Re-read the manual chapter carefully
2. Check the console for errors
3. Google the error message
4. Ask Claude or ChatGPT (it's allowed!)
5. As a last resort, email Dan

## Starter App Overview

The app currently has:
- Task list (add, complete, delete tasks)
- TypeScript types
- Basic styling
- Component structure

You're adding:
- Focus timer component
- Countdown logic
- Audio alerts
- Integration with task list

## Tech Stack

- React 18 with TypeScript
- Vite (fast dev server)
- Vitest (for testing)
- CSS (no framework - keep it simple)

## Grading

Your submission is graded on 7 criteria:
1. Personal questions answered (10 points)
2. Tests exist for timer component (10 points)
3. Tests written FIRST - Test-Driven Development (20 points bonus!)
4. Timer component renders (15 points)
5. Countdown works correctly (20 points)
6. Audio alert plays when timer ends (15 points)
7. Good judgment shown (caught the trap in Chapter 3) (10 points)

**Total possible: 100 points (or 110 with TDD bonus!)**

---

**Ready?** Open `MANUAL.md` and start with Chapter 1!

Good luck! 🚀
# Test workflow formatting fix - Wed Jan 14 20:51:39 -03 2026

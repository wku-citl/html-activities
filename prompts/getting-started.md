# Getting Started with AI-Powered Activity Customization

This guide will help you customize any of the HTML activity templates using AI tools like ChatGPT or Claude.

## Quick Start Process

1. **Try an activity** - Click any link from the main page to see it in action
2. **Download the source code** - Right-click → View Page Source → Save As HTML
3. **Use AI to customize** - Follow the prompts below
4. **Test your activity** - Open the HTML file locally to test
5. **Upload to your LMS** - Add to Blackboard, Canvas, etc.

---

## General Customization Prompt Template

Use this prompt structure for any activity:
```
I have an HTML [ACTIVITY TYPE] for [ORIGINAL SUBJECT].

I want to adapt it for my [YOUR SUBJECT] course to [YOUR GOAL].

Keep all the functionality ([LIST KEY FEATURES]) but replace the [ORIGINAL SUBJECT] content with [YOUR NEW CONTENT].

Here are my specific requirements:
- [REQUIREMENT 1]
- [REQUIREMENT 2]
- [REQUIREMENT 3]

Here's the HTML code: [PASTE CODE]
```

**Example:**
```
I have an HTML flashcard activity for psychology concepts.

I want to adapt it for my Spanish 101 course to help students practice vocabulary.

Keep all the functionality (flip cards, study mode, shuffle, mastery tracking) but replace the psychology content with 15 Spanish vocabulary words and their English translations.

Here are my specific requirements:
- Include common greetings and introductions
- Add audio pronunciation hints in the descriptions
- Keep the purple color scheme

Here's the HTML code: [PASTE CODE]
```

---

## Activity-Specific Prompts

### 📇 Flashcards

**Best for:** Vocabulary, definitions, key concepts, formulas

**Customization Prompt:**
```
I have an HTML flashcard activity. I need to create [NUMBER] flashcards for my [COURSE/TOPIC].

Each card should have:
- Front: [WHAT GOES ON FRONT]
- Back: [WHAT GOES ON BACK]

Keep the study mode toggle, mastery tracking, and shuffle features.

My [NUMBER] items are:
1. [ITEM 1]: [DEFINITION/ANSWER]
2. [ITEM 2]: [DEFINITION/ANSWER]
...

Here's the code: [PASTE CODE]
```

---

### 🌳 Decision Trees / Branching Scenarios

**Best for:** Case studies, clinical reasoning, troubleshooting, ethical dilemmas

**Customization Prompt:**
```
I have an HTML decision tree activity. I need to create a branching scenario for [YOUR CONTEXT].

The scenario should have:
- Starting scenario: [DESCRIBE INITIAL SITUATION]
- [NUMBER] decision points where users choose between [NUMBER] options
- Different outcomes based on choices

Decision points:
1. [DECISION 1]: Options: [A], [B], [C]
2. [DECISION 2]: Options: [A], [B]
...

Keep the progress tracking and visual design.

Here's the code: [PASTE CODE]
```

---

### 🔄 Sorting Activities

**Best for:** Classification, categorization, grouping concepts

**Customization Prompt:**
```
I have an HTML drag-and-drop sorting activity. I need students to sort [NUMBER] items into [NUMBER] categories.

Categories:
1. [CATEGORY 1]: [DESCRIPTION]
2. [CATEGORY 2]: [DESCRIPTION]

Items to sort:
- [ITEM 1] (belongs in [CATEGORY])
- [ITEM 2] (belongs in [CATEGORY])
...

Keep the drag-and-drop functionality, immediate feedback, and progress tracking.

Here's the code: [PASTE CODE]
```

---

### ✅ Checklists

**Best for:** Procedures, protocols, pre-activity checks, step-by-step processes

**Customization Prompt:**
```
I have an HTML checklist activity. I need a checklist for [YOUR PROCEDURE/PROTOCOL].

Main sections:
1. [SECTION 1]: [DESCRIPTION]
   - [ITEM 1]
   - [ITEM 2]
   
2. [SECTION 2]: [DESCRIPTION]
   - [ITEM 1]
   - [ITEM 2]

Keep the progress tracking and nested checkbox functionality.

Here's the code: [PASTE CODE]
```

---

### 📅 Timelines

**Best for:** Chronological events, sequences, historical periods

**Customization Prompt:**
```
I have an HTML timeline activity where students arrange events chronologically.

I need a timeline for [YOUR TOPIC] covering [TIME PERIOD].

Events to include:
1. [YEAR]: [EVENT NAME] - [BRIEF DESCRIPTION] - [SIGNIFICANCE]
2. [YEAR]: [EVENT NAME] - [BRIEF DESCRIPTION] - [SIGNIFICANCE]
...

Keep the click-to-select placement and immediate feedback features.

Here's the code: [PASTE CODE]
```

---

### 🛠️ Planning & Prioritization Tools

**Best for:** Project planning, goal setting, strategy development

**Customization Prompt:**
```
I have an HTML prioritization tool where users select 3-5 items from multiple categories.

I need this adapted for [YOUR CONTEXT].

Categories:
1. [CATEGORY 1]: [NUMBER] options
2. [CATEGORY 2]: [NUMBER] options

For each option, include:
- Title
- Brief description
- Implementation steps
- Time/resource requirements

Keep the select-and-generate-plan functionality.

Here's the code: [PASTE CODE]
```

---

### ✍️ Error Identification Activities

**Best for:** Editing practice, debugging, critical thinking

**Customization Prompt:**
```
I have an HTML error identification activity where students click highlighted text to reveal errors.

I need a [LENGTH] passage about [TOPIC] with [NUMBER] embedded errors of these types:
- [ERROR TYPE 1]
- [ERROR TYPE 2]
- [ERROR TYPE 3]

For each error, provide:
- What's wrong
- How to fix it
- The underlying rule/principle

Keep the click-to-reveal and progress tracking features.

Here's the code: [PASTE CODE]
```

---

## Tips for Best Results

### 1. Be Specific
❌ "Make this about science"
✅ "Create flashcards for 15 biology terms related to cellular respiration, including ATP, mitochondria, glycolysis..."

### 2. Provide Complete Content
Give AI all the content it needs rather than asking it to generate content. You know your discipline better than AI does.

### 3. Test Thoroughly
Always test the customized activity before sharing with students. Check:
- All content is accurate
- Interactive features work
- Links/navigation function properly
- Displays correctly on mobile devices

### 4. Iterate
If the first result isn't perfect, give AI feedback:
"This is close, but can you make these changes: [LIST SPECIFIC CHANGES]"

---

## Troubleshooting

**Problem:** Activity doesn't work after customization
**Solution:** Check for these common issues:
- Missing closing tags (`</div>`, `</script>`)
- Mismatched quotation marks
- Deleted essential JavaScript code
- Ask AI: "The activity isn't working. Can you check the code for errors?"

**Problem:** Content doesn't fit the layout
**Solution:** "The text is too long for the cards. Can you shorten descriptions to 2-3 sentences each?"

**Problem:** Want to change colors/fonts
**Solution:** "Can you change the color scheme to [YOUR COLORS] and use [FONT NAME] font?"

---

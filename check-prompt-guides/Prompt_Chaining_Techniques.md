# 🤖 Prompt Chaining Cheat Sheet for AI-Generated Reports

These templates help simulate **agent-like workflows** in a single AI prompt. Use them to guide the assistant through multi-step reasoning or report generation.

---

## 🧠 1. Guided Workflow (Full Chain in One Prompt)

```text
You are an AI assistant helping a farm business consultant prepare a draft annual report.

Follow these steps:
1. Summarise the production and financial data I provide.
2. Analyse one market outlook article or paragraph for insights.
3. Generate 2–3 strategic recommendations based on the above.
4. Combine the outputs into a one-page mock report with sections: Summary, Performance, Market Outlook, Strategy.

Use plain, professional English suitable for a WA farm client.

Here is the data:
<<<INSERT MOCK DATA TABLE>>>

Here is the market text:
<<<INSERT EXCERPT>>>
```

---

## 🧠 2. Modular Prompt Chain (Explicit Steps)

```text
You are a multi-step reasoning assistant. Break this task into steps and complete them sequentially:

Goal: Draft a mini farm business annual report using a dataset and a market summary.

Step 1: Summarise the table.
Step 2: Analyse the market excerpt.
Step 3: Write 3 strategy points.
Step 4: Compile everything into a report.

Output all four steps, clearly labelled.
```

---

## ⏸️ 3. Interactive Chain (Pause Between Steps)

```text
You are an AI assistant performing a four-step workflow. Complete step 1, then wait for me to type CONTINUE before moving to the next.

Steps:
1. Summarise the production data.
2. Analyse the market text.
3. Generate 3 strategy suggestions.
4. Draft a summary report.

Start by asking: "Ready to begin. May I proceed with step 1?"
```

---

## 🎓 Bonus Prompt Modifiers

Add these to the end of any prompt to adjust tone, format, or output:

- “Use plain English suitable for farm clients.”  
- “Format output with section headings.”  
- “Limit to 150 words per section.”  
- “Write like a trusted advisor, not a robot.”  
- “Make this suitable for pasting into a client email or Word report.”

---

> 🧠 These prompt chains let you simulate agent logic — reasoning, summarising, and combining information — without using any tools beyond ChatGPT, Claude, or Copilot Chat.

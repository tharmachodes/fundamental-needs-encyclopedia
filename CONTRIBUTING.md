# Contributing to the Fundamental Needs Encyclopedia

Welcome, student researchers! This guide explains how to contribute to our collaborative encyclopedia using GitHub.

## Our Workflow

We follow a simple but structured process to ensure quality and collaboration:

1. **Propose** → 2. **Branch** → 3. **Research & Write** → 4. **Review** → 5. **Publish**

---

## 1. Propose a Culture (Issue)

Before you start writing, you must propose your chosen culture to the class.

### How to create a proposal:
1. Go to the [Issues tab](https://github.com/tharmachodes/fundamental-needs-encyclopedia/issues) and click "New Issue".
2. Select the **"New Culture Proposal"** template (if available).
3. Fill in the required information:
   - **Group members** (list all students in your research team)
   - **Chosen culture** (e.g., "Ancient Sumer," "Inca Empire," "Modern Japan")
   - **Planned focus** (which fundamental needs will you research first?)
   - **Timeline** (when do you expect to complete your draft?)
4. Submit the issue. Your teacher will review it and assign the label `proposed`.

---

## 2. Create Your Workspace (Branch)

Once your proposal is approved, create a **branch** where you will do all your work.

### Branch naming convention:
- Use `feature/` followed by a short, descriptive name.
- Example: `feature/sumerian-culture`, `feature/inca-empire`

### How to create a branch (via GitHub Web):
1. Click the branch dropdown (usually says "main" near the top-left).
2. Type your new branch name (e.g., `feature/sumerian-culture`) and press Enter.
3. GitHub will automatically switch to that branch.

---

## 3. Research and Write (Files)

### Folder Structure:
All culture entries belong inside the `cultures/` directory. Create a new folder for your culture:

```
cultures/
└── ancient-sumer/          ← your culture folder
    ├── README.md           ← your main article
    └── images/             ← optional: store images here
```

### Writing your article:
1. Create a `README.md` file inside your culture folder.
2. Use Markdown to format your text.
3. Follow the **article template** (see `cultures/template/README.md` for guidance).
4. Organize your article using the Fundamental Needs headings:
   - `## Shelter`
   - `## Food`
   - `## Clothing`
   - etc.
5. Include **citations** for your sources (use footnotes or a "References" section).
6. Link to **public-domain or Creative Commons images** (do not upload copyrighted images without permission).

---

## 4. Submit for Review (Pull Request)

When your draft is ready, open a **Pull Request** (PR) to propose merging your branch into `main`.

### How to open a PR:
1. Go to the "Pull Requests" tab and click "New Pull Request".
2. Set **base** to `main` and **compare** to your branch (e.g., `feature/sumerian-culture`).
3. Write a clear title: `Add encyclopedia entry for [Culture Name]`.
4. In the description:
   - Summarize what you learned.
   - Mention any challenges or interesting discoveries.
   - Link to the original proposal issue (e.g., "Closes #1").
5. Click "Create Pull Request".

---

## 5. Review and Revision

Your teacher and classmates will review your PR using **inline comments** and **overall feedback**.

### What to expect:
- **Inline comments**: Suggestions or questions on specific lines of your `README.md`.
- **Review verdict**: The reviewer may "Approve," "Comment," or "Request Changes."
- If changes are requested, simply edit your files in the same branch and push again. The PR will update automatically.

### How to respond to feedback:
1. Read each comment carefully.
2. Make the necessary edits in your branch.
3. Commit and push your changes.
4. You may also reply to comments to ask for clarification or explain your reasoning.

---

## 6. Publication (Merge)

Once your PR is approved, your teacher will **squash and merge** it into the main branch.

### After merging:
- Your article is now part of the official encyclopedia!
- The original proposal issue will be closed with a comment linking to the PR.
- The `completed` label will be added to the issue.

---

## Style and Quality Guidelines

### Writing style:
- Write in clear, academic English.
- Use headings, lists, and bold/italic formatting to improve readability.
- Keep paragraphs concise (3–5 sentences).

### Citations:
- Use a consistent citation format (e.g., APA, MLA, or simple footnote links).
- Include a "References" or "Further Reading" section at the end.

### Images:
- Prefer images from public domain sources (e.g., Wikimedia Commons, NASA, Library of Congress).
- Always credit the image creator and provide a source link.
- Use Markdown image syntax: `![Alt text](URL)`

### Collaboration:
- Be respectful and constructive in all comments.
- Celebrate each other's discoveries!
- Ask for help if you're stuck—your teacher and peers are here to guide you.

---

## Need Help?

- **GitHub basics**: Check out [GitHub Docs](https://docs.github.com).
- **Markdown guide**: See [Markdown Cheatsheet](https://github.com/adam-p/markdown-here/wiki/Markdown-Cheatsheet).
- **Ask your teacher** for clarification on any step.

Happy researching! 🌍📚

*"The greatest sign of success for a teacher... is to be able to say, 'The children are now working as if I did not exist.'" – Maria Montessori*
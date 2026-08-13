SSSWriteups - HOW TO ADD WRITEUPS

SITE STRUCTURE

Homepage
  -> Category page
      -> Individual writeup

For example:

index.html
  -> categories/overthewire.html
      -> writeups/overthewire/bandit/level-0.html


ADDING A NEW WRITEUP

1. Create the HTML file inside the correct writeups/ folder.

Example:
writeups/overthewire/bandit/level-3.html

2. Copy an existing writeup HTML file and replace its content.

3. Add screenshots to:
assets/screenshots/

4. Open the category page and add a new card linking to your writeup.

Example:

<a class="latest-item" href="../writeups/overthewire/bandit/level-3.html">
  <div>
    <span class="tag">LEVEL 03 → 04</span>
    <h3>Bandit Level 3 → 4</h3>
    <p>Your short description.</p>
  </div>
  <span class="arrow">→</span>
</a>

IMPORTANT:
- The homepage stays clean.
- Clicking a category opens a separate category page.
- All writeups for that category are listed on that page.
- You can create hundreds of individual HTML writeups.
- No JavaScript, Node.js, npm, React or Vite is required.

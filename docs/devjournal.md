# DEVELOPMENT JOURNAL

---

## Date

March 5, 2026 – 6:00 PM

## Feature

## Implement starter HTML/CSS files after planning of file structuring;

## Goal

- Implement starter HTML structure and begin styles.css and animations.css for project requirements and rubric
- Layout of page setup including functional nav bar, header, footer

---

## Narrative / Log

Today I focused on building the starter code pages for all of the HTML. I also worked on incorporating basic CSS styling for the
styles.css sheet, and then I began the starter code for the animations.css

Example CSS used:

```css
body {
  font-family: Arial, sans-serif;
  background: #f5f5f5;
  line-height: 1.6;
}

header {
  background: #333;
  color: white;
  padding: 20px;
  text-align: center;
}

/* nav styles */
nav ul {
  list-style: none;
  padding: 0;
}
```

## Challenges/Debugging

I did not have any challenges implementing the files to get a basic, functional web application running. I made sure to include the basic semantic skeleton.

## Recap/Reflection

Recap: For the next development journal entry, the goal will be to implement more of the project HTML+CSS requirements.

---

## Date

March 8, 2026 – 8:10 AM

## Feature

Implement recipe card grid layout for the Recipes page.

---

## Goal

- Add recipe cards for appetizers, main dishes, and desserts
- Implement CSS Grid layout for recipe listings
- Link one recipe to the detailed recipe page
- Add placeholder recipes for future expansion

---

## Narrative / Log

Today I focused on building the recipes.html page structure.

I used CSS Grid to organize recipe cards inside each recipe category.  
The `.recipe-grid` container allows the layout to automatically adjust depending on screen size.

Example CSS used:

```css
.recipe-grid {
  display: grid;
  grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
  gap: 20px;
}
```

## Challenges/Debugging

    Any problems & solutions

## Recap/Reflection

---

## Date

March 8, 2026 – 2:00 PM

## Feature

Implement CSS transforms, transitions, animations; Implementation of Flexbox + Grid; Testing hero section styling

---

## Goal

- CSS Animations
- Implementation of Flexbox, Grid
- Index.html styling

---

## Narrative / Log

For this commit, I implemented more CSS animations such as transforms, transitions, etc. This commit also included the usage of flexbox + grid. Furthermore, did some hero section styling for the index.html (homepage)

Example CSS used:

```css
/* body takes up the full height of the viewport */
html,
body {
  height: 100%;
  margin: 0;
  display: flex;
  flex-direction: column;
}

.recipe-grid {
  display: grid;
  grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
  gap: 20px;
}
```

## Challenges/Debugging

    N/A

## Recap/Reflection

Recap: Plan to complete all of HTML

---

## Date

March 8, 2026 – 3:40 PM

## Feature

## Update footer text!

## Goal

- Implement footer changes, begin styling header/footer css

---

## Narrative / Log

For this commit, I focused on updating the footer relating to the copyright to make it consistent across all pages.

## Challenges/Debugging

N/A

## Recap/Reflection

Updated footer for better visual experience, next commit will be completing most, if not all HTML

---

## Date

March 8, 2026 – 3:48 PM

## Feature

CRISTIN'S COMMIT:
Completed implementation of the 6 food items featured;

---

## Goal

- Finished recipes for appetizers, entrees & desserts
- Include images of food items for visual experience
- Completed HTML

---

## Narrative / Log

In this commit, I (Cristin) completed the HTML for all of the foods within recipe.html. This includes the appetizers, entrees, and desserts.
Furthermore, there were an image included for each of the food item.

Example HTML used:

```html
<section class="recipe-category">
  <h3>Appetizers</h3>
  <p>Light dishes to start your meal.</p>

  <div class="recipe-grid">
    <div class="recipe-card">
      <img src="assets/loadedpotatoskins.jpg" alt="Loaded Potato Skins" />

      <div class="recipe-content">
        <h4>Loaded Potato Skins</h4>

        <p>
          Loaded potato skins are crispy potato halves topped with melted
          cheese, bacon, and green onions!
        </p>

        <a class="button" href="recipe-detail.html">View Recipe</a>
      </div>
    </div>

    <div class="recipe-card">
      <img src="assets/crabrangoons.jpeg" alt="Crab Rangoons" />

      <div class="recipe-content">
        <h4>Crab Rangoons</h4>

        <p>
          This Crab rangoon recipe is made with delicious crab and cream cheese
          filling wrapped in a wonton wrapper and fried to crispy prefection!
        </p>

        <a class="button" href="https://www.feedmi.org/crab-rangoon-recipe/"
          >View Recipe</a
        >
      </div>
    </div>
  </div>
</section>
```

## Challenges/Debugging

N/A

## Recap/Reflection

---

## Date

March 8, 2026 – 6:00 PM

## Feature

LAN'S PLANNED COMMIT: CONTACT.HTML

---

## Goal

- Completed HTML; marks the completion of all HTML files; can polish up css styling

---

## Narrative / Log

Today I focused on building the recipes.html page structure.

I used CSS Grid to organize recipe cards inside each recipe category.  
The `.recipe-grid` container allows the layout to automatically adjust depending on screen size.

Example HTML used:

```html
<form>
  <label>Name</label>
  <input type="text" name="name" />

  <label>Email</label>
  <input type="email" name="email" />

  <label>Message</label>
  <textarea name="message"></textarea>

  <button type="submit">Send Message</button>
</form>
```

## Challenges/Debugging

    N/A

## Recap/Reflection

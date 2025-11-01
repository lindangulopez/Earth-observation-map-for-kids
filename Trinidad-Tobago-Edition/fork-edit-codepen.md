# How to fork and edit the CodePen

---

## **Part 1: How to Fork and Edit the CodePen**

1. **Open the CodePen link**
   Click the CodePen link your teacher gave you. You should see the interactive map on the page.

2. **Sign in or sign up**
   To make your own copy, you need to be logged in. You can use Google or GitHub accounts to log in.

3. **Click “Fork”**
   At the top right of the CodePen page, you’ll see a button called **Fork**. Click it.

   * “Forking” means making your own copy of someone else’s code so you can change it without breaking the original.

4. **Start editing**

   * You’ll see three boxes: **HTML**, **CSS**, and **JS**.

     * HTML is like the skeleton or structure of your page.
     * CSS is how it looks—colors, fonts, and layout.
     * JS (JavaScript) is how it behaves or moves (this code doesn’t really use JS much).

5. **Change the map points**

   * In the HTML box, find the `<button class="map-point" ...>` sections.
   * You can change the text inside `<h2>` and `<p>` to name new places or write funny messages.
   * You can also move the points by changing the `top:` and `left:` percentages. For example:

     ```html
     <button class="map-point" style="top:50%;left:50%">
     ```

     moves that point to the middle of the map.

6. **Change colors or fonts (optional)**

   * In the CSS box, you can change colors by finding things like `background-color:` or `color:`.
   * You can change the font by editing the `link href` at the top, or pick another from Google Fonts.

7. **Save your CodePen**

   * Click **Save** at the top. You now have your own interactive map that you can share!

---

## **Part 2: Explaining the Code to 8-13 Year Olds**

1. **What this map does**

   * This map is a picture with **clickable points**.
   * When you click a point, it opens a little box with a name and description of a place.

2. **Breaking down the HTML**

   * `<h1>` is the title of your page:

     ```html
     <h1>Pure CSS Interactive Map</h1>
     ```

     → It just shows big letters at the top.

   * `<p>` is a paragraph of text:

     ```html
     <p class="description">Click the points to expand them.</p>
     ```

     → It gives instructions or extra info.

   * `<div class="distribution-map">` is like the **map container**.

     * Inside this, each `<button class="map-point">` is a **dot on the map**.

   * Each button has:

     ```html
     <div class="content">
       <div class="centered-y">
         <h2>Place Name</h2>
         <p>Description</p>
       </div>
     </div>
     ```

     → This is the **popup box** you see when you click the point.

3. **The `style="top:xx%;left:xx%"` part**

   * These numbers decide **where the dot appears** on the map.
   * Top = how far from the top, Left = how far from the left.

4. **Fonts**

   ```html
   <link href='//fonts.googleapis.com/css?family=Roboto' ...>
   ```

   → This just changes how the letters look on your page. Fancy letters!

5. **Clicking works with CSS**

   * Normally, buttons change style when clicked using CSS. That’s what makes the popup boxes appear.

---

✅ **Tips for students:**

* Try changing the text to your favorite places, pets, or video game locations.
* Experiment with colors in CSS—see what happens!
* Move the map points around with `top` and `left` and watch them jump to new places.



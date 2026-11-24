# 🧩 Extensions App — Version 3 Instructions

## 👋 Welcome!

In Version 3 you will let users add extensions, switch between light and dark mode, and load the extensions from an API.

## 🎯 Requirements

You will build a React app that:

- Has a form that adds a new extension
- Has a light and dark mode
- Loads its extensions from an API
- Is responsive and deployed to a Netlify URL

**User stories:**

- As a user, I can add a new extension with a form, and see its card right away
- As a user, I can switch the whole app between light and dark mode
- As a user, I see a loading message while the extensions load, and an error message if they cannot load

## 💎 Demo

The finished app: https://jazzy-gingersnap-f22954.netlify.app/

## 🔗 Resources

- **Finished app:** https://jazzy-gingersnap-f22954.netlify.app/
- **Starter code:** [`extensions-app`](https://github.com/ac-frontend/extensions-app)
- **Pseudo-code worksheet:** `pseudo-code.txt` in this folder
- **Documentation guides:** *(add link to the documentation guides)*

## 📝 Tips for building your project

See the tips and the commit message guide in the [main README](../README.md).

## Checkpoint 1: Add Extension Form

- [ ] A form with a name, a description and an Active checkbox
- [ ] The form is a component with **controlled inputs**
- [ ] Submitting adds a new card without reloading the page
- [ ] The form clears after it is submitted
- [ ] Name and description are required
- [ ] The new card works with the toggle, remove and filter
- [ ] Comments in your code
- [ ] You committed with meaningful messages, pushed, and deployed

---

## Checkpoint 2: Light and Dark Mode

- [ ] A `NavBar` component with the app name and a button
- [ ] The button switches between light and dark mode, and its icon shows which mode you will switch to
- [ ] The whole app changes: page, nav bar, form, buttons and cards
- [ ] The current mode is kept in **state**
- [ ] Comments in your code
- [ ] You committed with meaningful messages, pushed, and deployed

---

## Checkpoint 3: Load From an API and Finish

Fill out Part 2 of the `pseudo-code.txt` file before you start.

- [ ] The extensions are loaded from the API when the page opens, not imported from `data.js` (API link: https://raw.githubusercontent.com/ac-frontend/extensions-app-instructions/main/version-3/data.json)
- [ ] A loading message shows while they load
- [ ] An error message shows if they cannot load
- [ ] No errors in the browser console
- [ ] The app looks good on a phone-sized screen
- [ ] Your repo has a `README.md` with the app name, what it does, a screenshot and the link to your live site
- [ ] The code is clean: no unused files, comments where they help
- [ ] You committed with meaningful messages, pushed, and deployed

---

# 🚀 Roadmap

## 🧱 Components

At the very least, add these:

- **`ExtensionForm`**: the form that adds an extension
- **`NavBar`**: the app name and the light/dark button


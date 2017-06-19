***Code 201: Day 9***
**What happens when we open the page in the browser? [Using Salmon Cookie Lab]**
- Browser reads HTML
- Loads JS:
            1. Take stock of vars & function declarations & load into ?memory?
            2. Run executable

            function renderAll() {
              makeHeaderRow();
              *renderAllStores*; =======================> *for* () {};
                                                            allStoresrender[i];
              makeFooterRow();
            }

              **This the same as your .js code:**
              createTableHeaderRow();
              renderallStores();
              createTableFooterRow();

            3. Page is loaded
            4. Table has been rendered
            5. Turn on listener for the form.
            **WAIT...**
            6. User fills out form...SUBMIT!!!
            7. Lister hears event, invokes the handler.
            8. Grab data from form.
            9. Create a new store instances.
            10. Add new store to the allStores array:
                allStores.push(this);
            11.

**What happens when we create an instance?**
  - Calculate customers
  - Calculate cookies
  - Calculate Daily Total
  - Instance is pushed
  - Instance renders itself

*If your render method is calculating all of the entities in the objects, together; then you're going to have a problem; because your behaviors are not independent.

I missed Friday; but I am going through available resources; and trying to notate after catching up with my assignments.

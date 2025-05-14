# 🖥️ Console-program för skolhantering

## 📌 Projektsteg (Svenska)

- [ ] Skapa ett nytt console-program i C#  
- [ ] Skapa en enkel navigation i programmet som gör att användaren kan välja mellan följande funktioner:

  - [ ] **Hämta personal**  
        > Kan lösas med [ADO.NET](http://ADO.NET) och SQL, annars Entity Framework.  
        Användaren får välja om denne vill se alla anställda, eller bara inom en viss kategori, som t.ex. lärare.

  - [ ] **Hämta alla elever**  
        > Ska lösas med Entity Framework.  
        Användaren får välja sortering: på förnamn eller efternamn, samt stigande eller fallande.

  - [ ] **Hämta alla elever i en viss klass**  
        > Ska lösas med Entity Framework.  
        Användaren får först en lista med alla klasser, väljer en, och får därefter se elever i den klassen.  
        Extra: Låt användaren även välja sorteringsordning som i funktionen ovan.

  - [ ] **Hämta alla betyg som satts den senaste månaden**  
        > Kan lösas med [ADO.NET](http://ADO.NET) och SQL, annars Entity Framework.  
        Visar elevens namn, kursens namn och betyget.

  - [ ] **Lista alla kurser med snittbetyg, högsta och lägsta betyg**  
        > Kan lösas med [ADO.NET](http://ADO.NET) och SQL, annars Entity Framework.  
        Tips: Spara betyg som siffror för enklare hantering.

  - [ ] **Lägg till nya elever**  
        > Kan lösas med [ADO.NET](http://ADO.NET) och SQL, annars Entity Framework.  
        Användaren matar in elevdata som sparas i databasen.

  - [ ] **Lägg till ny personal**  
        > Ska lösas med Entity Framework.  
        Användaren matar in uppgifter om en ny anställd som sparas i databasen.

---

## 📌 Project Steps (English)

- [ ] Create a new console program in C#  
- [ ] Build a simple menu-based navigation system that lets the user choose between the following options:

  - [ ] **Retrieve staff**  
        > Can be solved using [ADO.NET](http://ADO.NET) and SQL, or Entity Framework.  
        User chooses to see either all staff or filter by category (e.g., teachers only).

  - [ ] **Retrieve all students**  
        > Must be implemented with Entity Framework.  
        User can choose sorting: by first or last name, ascending or descending.

  - [ ] **Retrieve all students in a specific class**  
        > Must be implemented with Entity Framework.  
        User is shown a list of classes, selects one, and sees all students in that class.  
        Extra: Let user choose sorting as in the option above.

  - [ ] **Retrieve all grades assigned in the past month**  
        > Can be solved with [ADO.NET](http://ADO.NET) and SQL, or Entity Framework.  
        Displays student's name, course name, and the grade.

  - [ ] **List all courses with average, highest, and lowest grades**  
        > Can be solved with [ADO.NET](http://ADO.NET) and SQL, or Entity Framework.  
        Tip: Store grades as numeric values for easier calculations.

  - [ ] **Add new students**  
        > Can be solved with [ADO.NET](http://ADO.NET) and SQL, or Entity Framework.  
        User can input student data which is then saved to the database.

  - [ ] **Add new staff**  
        > Must be implemented using Entity Framework.  
        User can input new staff data which is then stored in the database.

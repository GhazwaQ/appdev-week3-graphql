```
mutation movies_fntasyFiction {

 harryPotter: insertmovies_by_genre(
    value: { 
      genre:"Fantasy Fiction", 
      year:2001,
      title:"Harry Potter and the Philosopher's Stone",
      synopsis:"Harry Potter, an eleven-year-old orphan, discovers that he is a wizard and is invited to study at Hogwarts. Even as he escapes a dreary life and enters a world of magic, he finds trouble awaiting him.",
      duration:159,
      thumbnail:"https://imgur.com/dGES3X1"}) {
    value{title}
   }
}
```

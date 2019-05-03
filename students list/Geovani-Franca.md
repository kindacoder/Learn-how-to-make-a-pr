## Geovani Perez Franca 😎

````javascript
const apresentation = function(introduction, aboutMe){
  const person = {
    name = "Geovani Perez França";
    college = "FAM - Faculdade de Americana";
    branch = "Computer Science";
    githubId = "Geovani Franca";
    place = "Hortolândia - SP";
  };
  
  if(introduction) {
    console.info("Name", person.name, "🙌");
    console.info("College", person.college, "🎓");
    console.info("Branch", person.branch, "👍");
    console.info("Place", person.place, "🏠");
  }
  
  if(aboutMe) {
    console.info("Hello dudes, my name is Geovani and in the final year computer science student.")
    console.info("My areas of interest are: Web Development and Open Sources.");
    console.error("View my page about: https://about.me/geovanipfranca"
  }
}

window.load = function() {
  apresentation(true, true);
}
````

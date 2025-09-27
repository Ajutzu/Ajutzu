```javascript
class SoftwareEngineer {
  constructor() {
    this.name = "Aeron Jme Castillo";
    this.role = "BSIT NT Student";
    this.languageSpoken = ["en_US", "tl_PH"];
  }

  sayHi() {
    console.log("Thanks for dropping by, hope you find some of my work interesting.");
  }
}

const me = new SoftwareEngineer();
me.sayHi();
console.log(me);

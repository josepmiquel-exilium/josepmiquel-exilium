```javascript
class SoftwareDeveloper {
    constructor() {
        this.name = "Josep Miquel";
        this.role = "Software Developer";
        this.techStack = ["React", "NextJS", "Express.js", "Laravel", "VueJS", "Django"];
        this.portfolio = "exilium.cat";
        this.email = "josepmiquel@exilium.cat";
        this.languageSpoken = ["en_US", "fr_BE", "ca_CA", "es_ES"];
    }

    sayHi() {
        console.log("Thanks for dropping by, see you in Tatooine!");
    }
}

const me = new SoftwareDeveloper();
me.sayHi();
```

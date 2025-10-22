```js
// Software Developer passionate about creating clean, efficient, and user-friendly web applications.  
// I enjoy working with both frontend and backend technologies.
// Always curious about learning new tools and frameworks.

class SoftwareDeveloper {
    name = "Josep Miquel";
    role = "Software Developer";
    techStack = [
        "JavaScript",
        "TypeScript",
        "React",
        "Next.js",
        "Express.js",
        "Laravel",
        "Vue.js",
        "Django"
    ];
    portfolio = "https://exilium.cat";
    email = "josepmiquel@exilium.cat";
    languagesSpoken = ["en_US", "fr_BE", "ca_CA", "es_ES"];

    sayHi = () => {
        console.log("👋 Thanks for stopping by, see you in Tatooine!");
    };
}

const josep = new SoftwareDeveloper();
josep.sayHi();

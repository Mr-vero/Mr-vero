<h1 align="center">Hi 👋, I'm Irvan</h1>
<h3 align="center">A passionate problem solver exploring the vast realms of technology.</h3>

<p align="left"> <a href="https://github.com/ryo-ma/github-profile-trophy"><img src="https://github-profile-trophy.vercel.app/?username=mr-vero" alt="mr-vero" /></a> </p>

<p align="left"> <a href="https://twitter.com/" target="blank"><img src="https://img.shields.io/twitter/follow/?logo=twitter&style=for-the-badge" alt="" /></a> </p>

- 🔭 I’m currently building [SideQuests](https://sidequests.app)

- 🌱 I’m currently learning **To Speak Italian**

- 👯 I’m looking to collaborate on **Positive Impact**

- 📫 How to reach me **Mr.vero@usa.com**

<h3 align="left">Connect with me:</h3>
<p align="left">
</p>

```ts
/**
 * @fileoverview
 * 
 * Developer: Mr-vero
 * GitHub: https://github.com/Mr-vero
 * Interests: Hybrid Technology, Artificial Intelligence, All things tech
 * Learning: Italian
 * Collaboration Criteria: Positive Impact
 */

/**
 * Developer class representing a coding enthusiast.
 */
class Developer {
    /**
     * GitHub username of the developer.
     * @type {string}
     */
    private username: string;

    /**
     * Array of developer interests.
     * @type {string[]}
     */
    private interests: string[];

    /**
     * Current learning focus.
     * @type {string}
     */
    private learning: string;

    /**
     * Criteria for collaboration.
     * @type {string}
     */
    private collaborationCriteria: string;

    /**
     * Constructor for the Developer class.
     * @param {string} username - The GitHub username of the developer.
     */
    constructor(username: string) {
        this.username = username;
        this.interests = ["Hybrid Technology", "Artificial Intelligence", "All things tech"];
        this.learning = "Italian";
        this.collaborationCriteria = "Positive Impact";
    }

    /**
     * Method providing a detailed introduction.
     * @returns {string} - Introduction string.
     */
    aboutMe(): string {
        return `
         👋 Hello, I'm ${this.username} - a passionate coder exploring the vast realms of technology.
        🚀 My GitHub: [${this.username}](https://github.com/${this.username})
        
        💡 Interests: ${this.interests.join(', ')}
        📚 Currently mastering the art of speaking ${this.learning}.
        🌟 Eagerly seeking collaborations aligned with my criteria for creating ${this.collaborationCriteria}.
        `;
    }

    /**
     * Method providing contact information.
     * @returns {string} - Contact information.
     */
    contactMe(): string {
        return `Connect with me via email: ${this.username}@usa.com`;
    }
}

// Create an instance of the Developer class
const mrVero: Developer = new Developer("@Mr-vero");

// Display the JavaScript Programming Bio
console.log(mrVero.aboutMe());
console.log(mrVero.contactMe());

```



<details><summary><b>Output</b></summary>

```ts
"use strict";
/**
 * @fileoverview
 *
 * Developer: Mr-vero
 * GitHub: https://github.com/Mr-vero
 * Interests: Hybrid Technology, Artificial Intelligence, All things tech
 * Learning: Italian
 * Collaboration Criteria: Positive Impact
 */
/**
 * Developer class representing a coding enthusiast.
 */
class Developer {
    /**
     * Constructor for the Developer class.
     * @param {string} username - The GitHub username of the developer.
     */
    constructor(username) {
        this.username = username;
        this.interests = ["Hybrid Technology", "Artificial Intelligence", "All things tech"];
        this.learning = "Italian";
        this.collaborationCriteria = "Positive Impact";
    }
    /**
     * Method providing a detailed introduction.
     * @returns {string} - Introduction string.
     */
    aboutMe() {
        return `
         👋 Hello, I'm ${this.username} - a passionate coder exploring the vast realms of technology.
        🚀 My GitHub: [${this.username}](https://github.com/${this.username})
        
        💡 Interests: ${this.interests.join(', ')}
        📚 Currently mastering the art of speaking ${this.learning}.
        🌟 Eagerly seeking collaborations aligned with my criteria for creating ${this.collaborationCriteria}.
        `;
    }
    /**
     * Method providing contact information.
     * @returns {string} - Contact information.
     */
    contactMe() {
        return `Connect with me via email: ${this.username}@usa.com`;
    }
}
// Create an instance of the Developer class
const mrVero = new Developer("@Mr-vero");
// Display the JavaScript Programming Bio
console.log(mrVero.aboutMe());
console.log(mrVero.contactMe());

```


</details>


<details><summary><b>Compiler Options</b></summary>

```json
{
  "compilerOptions": {
    "strict": true,
    "noImplicitAny": true,
    "strictNullChecks": true,
    "strictFunctionTypes": true,
    "strictPropertyInitialization": true,
    "strictBindCallApply": true,
    "noImplicitThis": true,
    "noImplicitReturns": true,
    "alwaysStrict": true,
    "esModuleInterop": true,
    "declaration": true,
    "target": "ES2017",
    "jsx": "react",
    "module": "ESNext",
    "moduleResolution": "node"
  }
}
```


</details>

**Playground Link:** [Provided](https://www.typescriptlang.org/play?#code/PQKhCgAIUgBAzAlgGwKYHsBuqBOnGoDuUMJkAIqtsugA64BckAsjgLTY7pkDiiALgAkArgCMmAC379aAZwbBgAcwESxAOgDG6ALbBWHXN2iQAkgDt+uVLP7zIggJ6iciACaQAKqk0Tz6GiVHABpIAEEcfkQkTUQAQ2QzS1RkZEQlVHNNVFCw1Mh+CURzJVkCnwkyABlUOJxzYqUmU34E+PMyAGEA5DjRdBw4qPRzSE7XK1c4pgAFdFkBRGwzHVo4zX4SYHBwUAgTSmo6XEhNXtkynFRaK9lMqJLIONP0N0bIe7UFuNt1LfAzj8yocUsccJAAN5QSAwvbQmEmPhCMSQYR3epxHSoSDoeAFCTYtxUUH0HB-BEwmCwfiOeiQ2yuEoAX3hlO2FJuSyG2LRuHMmNQTAZjQA3DsKXCKSYIoNHDi8USjqTIMVJjY7OSKVSaXSIcKSgBtAC6LKlIHZCM5mG5KuStzsQv4jKUxrFrMlWrGwhwV0skDQdQaj3g6E0aM1CO1tOxeqdjVNWotMKtNoD9UajudbolYFZJnGAlw8UgIfB2lSfQGQ0QIwjlLgOpj+qUCcjScgKasLwr-UGw3MBcm8UzovFCI9kbGIwZwg2AxL88K2JBNGVgIudZMsDWgx09LjzNR6P5WMgbC8BMgSJEoiPfIF8vxhOJq9wm-NrO05hnc5wAApeQxLERxKABKSE8wRQpEFkdRAJPbEAF47yA1AxSlKCilg1VrFsMpkINAAiJwXHcLwKn8QJHEI0JCIiKIYniRILCsVJ0kybIaMgOj8mgkoyisXxCKNdCMPxGD1DTIMlEgZDCJaNo4nMQjRIw6DYPLXpe2rEZByLZ45LmBYomWUxVnWfgVNZFl3VzM0WFQQpXg7Lh8DeR5niJVoUFQDxVS4NxZ37d84CufhvW-fdnSZM8kidV4gprUZm3fdtK2EfhmFQP9QJAmSoTEyAwoiyAAANIIRQBeDcAaR2HBSGhQlMAByPcABIIXUuDjwFGLz2eNYLiSm1tCJcFUAAD1oGhnSfSBrVsIramQHQylxcpfEo9Agk3KrAAC9lg5WvMQmANdrOvgnqjT-KQZHkRQVEKDRtD0M6sK6+8sSZUCKsgH7KsAQp24twh1IFeiScPtWCACt0GKP8mtCJrQNbKVKsALZ2vR9e5kDlHQfiHR4lyeSJH1keg4gAa3eMHYKk+MdphQAeDcAfH3IAAUTiDIcBxyA7lQKnHk0ys+ySso2iUcxfMgQhVEgHQ5U0CZ9IXMsrmrR4aa0HphZ0gclamJkGbK1TIBsnN9k9LKnI8G4sHcd4v1aDZbVLPHgrzKlivqMpY2i2LuksCyXYGN2ktSz8RidzLsty3mD3yn6vdGUqA8l52ZcKOXsXwZ5UDxlAmE1i7PtgNE4i1nRSpNlkbMUMY1a7JTbVsJTskfImVzBU5zlkAFp34OWcAANSMJhO+VZDJcICgXzBP9CNgAxOHQQjQLdOvyBgqa4jlImACk4mtABlRXEFoAeZi4JRdx0d4ACEaz778AlQSStr-HRh6MdR0ujnK16frIF+b8lAfy-lwLWgcNhZX-mKIAA)

      

<p><img align="center" src="https://github-readme-stats.vercel.app/api/top-langs?username=mr-vero&show_icons=true&locale=en&layout=compact" alt="mr-vero" /></p>


<h3 align="left">Languages and Tools:</h3>
<p align="left"> <a href="https://developer.android.com" target="_blank" rel="noreferrer"> <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/android/android-original-wordmark.svg" alt="android" width="40" height="40"/> </a> <a href="https://angular.io" target="_blank" rel="noreferrer"> <img src="https://angular.io/assets/images/logos/angular/angular.svg" alt="angular" width="40" height="40"/> </a> <a href="https://cordova.apache.org/" target="_blank" rel="noreferrer"> <img src="https://www.vectorlogo.zone/logos/apache_cordova/apache_cordova-icon.svg" alt="apachecordova" width="40" height="40"/> </a> <a href="https://www.arduino.cc/" target="_blank" rel="noreferrer"> <img src="https://cdn.worldvectorlogo.com/logos/arduino-1.svg" alt="arduino" width="40" height="40"/> </a> <a href="https://aws.amazon.com" target="_blank" rel="noreferrer"> <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/amazonwebservices/amazonwebservices-original-wordmark.svg" alt="aws" width="40" height="40"/> </a> <a href="https://azure.microsoft.com/en-in/" target="_blank" rel="noreferrer"> <img src="https://www.vectorlogo.zone/logos/microsoft_azure/microsoft_azure-icon.svg" alt="azure" width="40" height="40"/> </a> <a href="https://babeljs.io/" target="_blank" rel="noreferrer"> <img src="https://www.vectorlogo.zone/logos/babeljs/babeljs-icon.svg" alt="babel" width="40" height="40"/> </a> <a href="https://www.gnu.org/software/bash/" target="_blank" rel="noreferrer"> <img src="https://www.vectorlogo.zone/logos/gnu_bash/gnu_bash-icon.svg" alt="bash" width="40" height="40"/> </a> <a href="https://www.blender.org/" target="_blank" rel="noreferrer"> <img src="https://download.blender.org/branding/community/blender_community_badge_white.svg" alt="blender" width="40" height="40"/> </a> <a href="https://getbootstrap.com" target="_blank" rel="noreferrer"> <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/bootstrap/bootstrap-plain-wordmark.svg" alt="bootstrap" width="40" height="40"/> </a> <a href="https://canvasjs.com" target="_blank" rel="noreferrer"> <img src="https://raw.githubusercontent.com/Hardik0307/Hardik0307/master/assets/canvasjs-charts.svg" alt="canvasjs" width="40" height="40"/> </a> <a href="https://cassandra.apache.org/" target="_blank" rel="noreferrer"> <img src="https://www.vectorlogo.zone/logos/apache_cassandra/apache_cassandra-icon.svg" alt="cassandra" width="40" height="40"/> </a> <a href="https://www.chartjs.org" target="_blank" rel="noreferrer"> <img src="https://www.chartjs.org/media/logo-title.svg" alt="chartjs" width="40" height="40"/> </a> <a href="https://circleci.com" target="_blank" rel="noreferrer"> <img src="https://www.vectorlogo.zone/logos/circleci/circleci-icon.svg" alt="circleci" width="40" height="40"/> </a> <a href="https://www.cockroachlabs.com/product/cockroachdb/" target="_blank" rel="noreferrer"> <img src="https://cdn.worldvectorlogo.com/logos/cockroachdb.svg" alt="cockroachdb" width="40" height="40"/> </a> <a href="https://couchdb.apache.org/" target="_blank" rel="noreferrer"> <img src="https://raw.githubusercontent.com/devicons/devicon/0d6c64dbbf311879f7d563bfc3ccf559f9ed111c/icons/couchdb/couchdb-original.svg" alt="couchdb" width="40" height="40"/> </a> <a href="https://www.cypress.io" target="_blank" rel="noreferrer"> <img src="https://raw.githubusercontent.com/simple-icons/simple-icons/6e46ec1fc23b60c8fd0d2f2ff46db82e16dbd75f/icons/cypress.svg" alt="cypress" width="40" height="40"/> </a> <a href="https://d3js.org/" target="_blank" rel="noreferrer"> <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/d3js/d3js-original.svg" alt="d3js" width="40" height="40"/> </a> <a href="https://dart.dev" target="_blank" rel="noreferrer"> <img src="https://www.vectorlogo.zone/logos/dartlang/dartlang-icon.svg" alt="dart" width="40" height="40"/> </a> <a href="https://www.djangoproject.com/" target="_blank" rel="noreferrer"> <img src="https://cdn.worldvectorlogo.com/logos/django.svg" alt="django" width="40" height="40"/> </a> <a href="https://www.docker.com/" target="_blank" rel="noreferrer"> <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/docker/docker-original-wordmark.svg" alt="docker" width="40" height="40"/> </a> <a href="https://dotnet.microsoft.com/" target="_blank" rel="noreferrer"> <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/dot-net/dot-net-original-wordmark.svg" alt="dotnet" width="40" height="40"/> </a> <a href="https://www.elastic.co" target="_blank" rel="noreferrer"> <img src="https://www.vectorlogo.zone/logos/elastic/elastic-icon.svg" alt="elasticsearch" width="40" height="40"/> </a> <a href="https://www.electronjs.org" target="_blank" rel="noreferrer"> <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/electron/electron-original.svg" alt="electron" width="40" height="40"/> </a> <a href="https://expressjs.com" target="_blank" rel="noreferrer"> <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/express/express-original-wordmark.svg" alt="express" width="40" height="40"/> </a> <a href="https://www.figma.com/" target="_blank" rel="noreferrer"> <img src="https://www.vectorlogo.zone/logos/figma/figma-icon.svg" alt="figma" width="40" height="40"/> </a> <a href="https://firebase.google.com/" target="_blank" rel="noreferrer"> <img src="https://www.vectorlogo.zone/logos/firebase/firebase-icon.svg" alt="firebase" width="40" height="40"/> </a> <a href="https://flask.palletsprojects.com/" target="_blank" rel="noreferrer"> <img src="https://www.vectorlogo.zone/logos/pocoo_flask/pocoo_flask-icon.svg" alt="flask" width="40" height="40"/> </a> <a href="https://flutter.dev" target="_blank" rel="noreferrer"> <img src="https://www.vectorlogo.zone/logos/flutterio/flutterio-icon.svg" alt="flutter" width="40" height="40"/> </a> <a href="https://www.framer.com/" target="_blank" rel="noreferrer"> <img src="https://www.vectorlogo.zone/logos/framer/framer-icon.svg" alt="framer" width="40" height="40"/> </a> <a href="https://www.gatsbyjs.com/" target="_blank" rel="noreferrer"> <img src="https://www.vectorlogo.zone/logos/gatsbyjs/gatsbyjs-icon.svg" alt="gatsby" width="40" height="40"/> </a> <a href="https://cloud.google.com" target="_blank" rel="noreferrer"> <img src="https://www.vectorlogo.zone/logos/google_cloud/google_cloud-icon.svg" alt="gcp" width="40" height="40"/> </a> <a href="https://git-scm.com/" target="_blank" rel="noreferrer"> <img src="https://www.vectorlogo.zone/logos/git-scm/git-scm-icon.svg" alt="git" width="40" height="40"/> </a> <a href="https://golang.org" target="_blank" rel="noreferrer"> <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/go/go-original.svg" alt="go" width="40" height="40"/> </a> <a href="https://grafana.com" target="_blank" rel="noreferrer"> <img src="https://www.vectorlogo.zone/logos/grafana/grafana-icon.svg" alt="grafana" width="40" height="40"/> </a> <a href="https://graphql.org" target="_blank" rel="noreferrer"> <img src="https://www.vectorlogo.zone/logos/graphql/graphql-icon.svg" alt="graphql" width="40" height="40"/> </a> <a href="https://gulpjs.com" target="_blank" rel="noreferrer"> <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/gulp/gulp-plain.svg" alt="gulp" width="40" height="40"/> </a> <a href="https://hadoop.apache.org/" target="_blank" rel="noreferrer"> <img src="https://www.vectorlogo.zone/logos/apache_hadoop/apache_hadoop-icon.svg" alt="hadoop" width="40" height="40"/> </a> <a href="https://www.haskell.org/" target="_blank" rel="noreferrer"> <img src="https://upload.wikimedia.org/wikipedia/commons/1/1c/Haskell-Logo.svg" alt="haskell" width="40" height="40"/> </a> <a href="https://heroku.com" target="_blank" rel="noreferrer"> <img src="https://www.vectorlogo.zone/logos/heroku/heroku-icon.svg" alt="heroku" width="40" height="40"/> </a> <a href="https://hive.apache.org/" target="_blank" rel="noreferrer"> <img src="https://www.vectorlogo.zone/logos/apache_hive/apache_hive-icon.svg" alt="hive" width="40" height="40"/> </a> <a href="https://www.w3.org/html/" target="_blank" rel="noreferrer"> <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/html5/html5-original-wordmark.svg" alt="html5" width="40" height="40"/> </a> <a href="https://ifttt.com/" target="_blank" rel="noreferrer"> <img src="https://www.vectorlogo.zone/logos/ifttt/ifttt-ar21.svg" alt="ifttt" width="40" height="40"/> </a> <a href="https://www.adobe.com/in/products/illustrator.html" target="_blank" rel="noreferrer"> <img src="https://www.vectorlogo.zone/logos/adobe_illustrator/adobe_illustrator-icon.svg" alt="illustrator" width="40" height="40"/> </a> <a href="https://ionicframework.com" target="_blank" rel="noreferrer"> <img src="https://upload.wikimedia.org/wikipedia/commons/d/d1/Ionic_Logo.svg" alt="ionic" width="40" height="40"/> </a> <a href="https://jasmine.github.io/" target="_blank" rel="noreferrer"> <img src="https://www.vectorlogo.zone/logos/jasmine/jasmine-icon.svg" alt="jasmine" width="40" height="40"/> </a> <a href="https://developer.mozilla.org/en-US/docs/Web/JavaScript" target="_blank" rel="noreferrer"> <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/javascript/javascript-original.svg" alt="javascript" width="40" height="40"/> </a> <a href="https://www.jenkins.io" target="_blank" rel="noreferrer"> <img src="https://www.vectorlogo.zone/logos/jenkins/jenkins-icon.svg" alt="jenkins" width="40" height="40"/> </a> <a href="https://jestjs.io" target="_blank" rel="noreferrer"> <img src="https://www.vectorlogo.zone/logos/jestjsio/jestjsio-icon.svg" alt="jest" width="40" height="40"/> </a> <a href="https://kafka.apache.org/" target="_blank" rel="noreferrer"> <img src="https://www.vectorlogo.zone/logos/apache_kafka/apache_kafka-icon.svg" alt="kafka" width="40" height="40"/> </a> <a href="https://karma-runner.github.io/latest/index.html" target="_blank" rel="noreferrer"> <img src="https://raw.githubusercontent.com/detain/svg-logos/780f25886640cef088af994181646db2f6b1a3f8/svg/karma.svg" alt="karma" width="40" height="40"/> </a> <a href="https://www.elastic.co/kibana" target="_blank" rel="noreferrer"> <img src="https://www.vectorlogo.zone/logos/elasticco_kibana/elasticco_kibana-icon.svg" alt="kibana" width="40" height="40"/> </a> <a href="https://kubernetes.io" target="_blank" rel="noreferrer"> <img src="https://www.vectorlogo.zone/logos/kubernetes/kubernetes-icon.svg" alt="kubernetes" width="40" height="40"/> </a> <a href="https://www.linux.org/" target="_blank" rel="noreferrer"> <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/linux/linux-original.svg" alt="linux" width="40" height="40"/> </a> <a href="https://mariadb.org/" target="_blank" rel="noreferrer"> <img src="https://www.vectorlogo.zone/logos/mariadb/mariadb-icon.svg" alt="mariadb" width="40" height="40"/> </a> <a href="https://www.mathworks.com/" target="_blank" rel="noreferrer"> <img src="https://upload.wikimedia.org/wikipedia/commons/2/21/Matlab_Logo.png" alt="matlab" width="40" height="40"/> </a> <a href="https://mochajs.org" target="_blank" rel="noreferrer"> <img src="https://www.vectorlogo.zone/logos/mochajs/mochajs-icon.svg" alt="mocha" width="40" height="40"/> </a> <a href="https://www.mongodb.com/" target="_blank" rel="noreferrer"> <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/mongodb/mongodb-original-wordmark.svg" alt="mongodb" width="40" height="40"/> </a> <a href="https://www.microsoft.com/en-us/sql-server" target="_blank" rel="noreferrer"> <img src="https://www.svgrepo.com/show/303229/microsoft-sql-server-logo.svg" alt="mssql" width="40" height="40"/> </a> <a href="https://www.mysql.com/" target="_blank" rel="noreferrer"> <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/mysql/mysql-original-wordmark.svg" alt="mysql" width="40" height="40"/> </a> <a href="https://nestjs.com/" target="_blank" rel="noreferrer"> <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/nestjs/nestjs-plain.svg" alt="nestjs" width="40" height="40"/> </a> <a href="https://nextjs.org/" target="_blank" rel="noreferrer"> <img src="https://cdn.worldvectorlogo.com/logos/nextjs-2.svg" alt="nextjs" width="40" height="40"/> </a> <a href="https://www.nginx.com" target="_blank" rel="noreferrer"> <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/nginx/nginx-original.svg" alt="nginx" width="40" height="40"/> </a> <a href="https://nodejs.org" target="_blank" rel="noreferrer"> <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/nodejs/nodejs-original-wordmark.svg" alt="nodejs" width="40" height="40"/> </a> <a href="https://opencv.org/" target="_blank" rel="noreferrer"> <img src="https://www.vectorlogo.zone/logos/opencv/opencv-icon.svg" alt="opencv" width="40" height="40"/> </a> <a href="https://openresty.org/" target="_blank" rel="noreferrer"> <img src="https://openresty.org/images/logo.png" alt="openresty" width="40" height="40"/> </a> <a href="https://www.oracle.com/" target="_blank" rel="noreferrer"> <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/oracle/oracle-original.svg" alt="oracle" width="40" height="40"/> </a> <a href="https://pandas.pydata.org/" target="_blank" rel="noreferrer"> <img src="https://raw.githubusercontent.com/devicons/devicon/2ae2a900d2f041da66e950e4d48052658d850630/icons/pandas/pandas-original.svg" alt="pandas" width="40" height="40"/> </a> <a href="https://www.perl.org/" target="_blank" rel="noreferrer"> <img src="https://api.iconify.design/logos-perl.svg" alt="perl" width="40" height="40"/> </a> <a href="https://www.photoshop.com/en" target="_blank" rel="noreferrer"> <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/photoshop/photoshop-line.svg" alt="photoshop" width="40" height="40"/> </a> <a href="https://www.php.net" target="_blank" rel="noreferrer"> <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/php/php-original.svg" alt="php" width="40" height="40"/> </a> <a href="https://www.postgresql.org" target="_blank" rel="noreferrer"> <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/postgresql/postgresql-original-wordmark.svg" alt="postgresql" width="40" height="40"/> </a> <a href="https://postman.com" target="_blank" rel="noreferrer"> <img src="https://www.vectorlogo.zone/logos/getpostman/getpostman-icon.svg" alt="postman" width="40" height="40"/> </a> <a href="https://github.com/puppeteer/puppeteer" target="_blank" rel="noreferrer"> <img src="https://www.vectorlogo.zone/logos/pptrdev/pptrdev-official.svg" alt="puppeteer" width="40" height="40"/> </a> <a href="https://www.python.org" target="_blank" rel="noreferrer"> <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/python/python-original.svg" alt="python" width="40" height="40"/> </a> <a href="https://pytorch.org/" target="_blank" rel="noreferrer"> <img src="https://www.vectorlogo.zone/logos/pytorch/pytorch-icon.svg" alt="pytorch" width="40" height="40"/> </a> <a href="https://www.rabbitmq.com" target="_blank" rel="noreferrer"> <img src="https://www.vectorlogo.zone/logos/rabbitmq/rabbitmq-icon.svg" alt="rabbitMQ" width="40" height="40"/> </a> <a href="https://rubyonrails.org" target="_blank" rel="noreferrer"> <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/rails/rails-original-wordmark.svg" alt="rails" width="40" height="40"/> </a> <a href="https://reactjs.org/" target="_blank" rel="noreferrer"> <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/react/react-original-wordmark.svg" alt="react" width="40" height="40"/> </a> <a href="https://reactnative.dev/" target="_blank" rel="noreferrer"> <img src="https://reactnative.dev/img/header_logo.svg" alt="reactnative" width="40" height="40"/> </a> <a href="https://redis.io" target="_blank" rel="noreferrer"> <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/redis/redis-original-wordmark.svg" alt="redis" width="40" height="40"/> </a> <a href="https://www.ruby-lang.org/en/" target="_blank" rel="noreferrer"> <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/ruby/ruby-original.svg" alt="ruby" width="40" height="40"/> </a> <a href="https://sass-lang.com" target="_blank" rel="noreferrer"> <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/sass/sass-original.svg" alt="sass" width="40" height="40"/> </a> <a href="https://www.scala-lang.org" target="_blank" rel="noreferrer"> <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/scala/scala-original.svg" alt="scala" width="40" height="40"/> </a> <a href="https://scikit-learn.org/" target="_blank" rel="noreferrer"> <img src="https://upload.wikimedia.org/wikipedia/commons/0/05/Scikit_learn_logo_small.svg" alt="scikit_learn" width="40" height="40"/> </a> <a href="https://sculpin.io/" target="_blank" rel="noreferrer"> <img src="https://gist.githubusercontent.com/vivek32ta/c7f7bf583c1fb1c58d89301ea40f37fd/raw/1782aef8672484698c0dd407f900c4a329ed5bc4/sculpin.svg" alt="sculpin" width="40" height="40"/> </a> <a href="https://seaborn.pydata.org/" target="_blank" rel="noreferrer"> <img src="https://seaborn.pydata.org/_images/logo-mark-lightbg.svg" alt="seaborn" width="40" height="40"/> </a> <a href="https://www.selenium.dev" target="_blank" rel="noreferrer"> <img src="https://raw.githubusercontent.com/detain/svg-logos/780f25886640cef088af994181646db2f6b1a3f8/svg/selenium-logo.svg" alt="selenium" width="40" height="40"/> </a> <a href="https://www.sketch.com/" target="_blank" rel="noreferrer"> <img src="https://www.vectorlogo.zone/logos/sketchapp/sketchapp-icon.svg" alt="sketch" width="40" height="40"/> </a> <a href="https://lucene.apache.org/solr/" target="_blank" rel="noreferrer"> <img src="https://www.vectorlogo.zone/logos/apache_solr/apache_solr-icon.svg" alt="solr" width="40" height="40"/> </a> <a href="https://spring.io/" target="_blank" rel="noreferrer"> <img src="https://www.vectorlogo.zone/logos/springio/springio-icon.svg" alt="spring" width="40" height="40"/> </a> <a href="https://www.sqlite.org/" target="_blank" rel="noreferrer"> <img src="https://www.vectorlogo.zone/logos/sqlite/sqlite-icon.svg" alt="sqlite" width="40" height="40"/> </a> <a href="https://svelte.dev" target="_blank" rel="noreferrer"> <img src="https://upload.wikimedia.org/wikipedia/commons/1/1b/Svelte_Logo.svg" alt="svelte" width="40" height="40"/> </a> <a href="https://symfony.com" target="_blank" rel="noreferrer"> <img src="https://symfony.com/logos/symfony_black_03.svg" alt="symfony" width="40" height="40"/> </a> <a href="https://tailwindcss.com/" target="_blank" rel="noreferrer"> <img src="https://www.vectorlogo.zone/logos/tailwindcss/tailwindcss-icon.svg" alt="tailwind" width="40" height="40"/> </a> <a href="https://www.tensorflow.org" target="_blank" rel="noreferrer"> <img src="https://www.vectorlogo.zone/logos/tensorflow/tensorflow-icon.svg" alt="tensorflow" width="40" height="40"/> </a> <a href="https://travis-ci.org" target="_blank" rel="noreferrer"> <img src="https://www.vectorlogo.zone/logos/travis-ci/travis-ci-icon.svg" alt="travisci" width="40" height="40"/> </a> <a href="https://www.typescriptlang.org/" target="_blank" rel="noreferrer"> <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/typescript/typescript-original.svg" alt="typescript" width="40" height="40"/> </a> <a href="https://unity.com/" target="_blank" rel="noreferrer"> <img src="https://www.vectorlogo.zone/logos/unity3d/unity3d-icon.svg" alt="unity" width="40" height="40"/> </a> <a href="https://unrealengine.com/" target="_blank" rel="noreferrer"> <img src="https://raw.githubusercontent.com/kenangundogan/fontisto/036b7eca71aab1bef8e6a0518f7329f13ed62f6b/icons/svg/brand/unreal-engine.svg" alt="unreal" width="40" height="40"/> </a> <a href="https://www.vagrantup.com/" target="_blank" rel="noreferrer"> <img src="https://www.vectorlogo.zone/logos/vagrantup/vagrantup-icon.svg" alt="vagrant" width="40" height="40"/> </a> <a href="https://vuejs.org/" target="_blank" rel="noreferrer"> <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/vuejs/vuejs-original-wordmark.svg" alt="vuejs" width="40" height="40"/> </a> <a href="https://webpack.js.org" target="_blank" rel="noreferrer"> <img src="https://raw.githubusercontent.com/devicons/devicon/d00d0969292a6569d45b06d3f350f463a0107b0d/icons/webpack/webpack-original-wordmark.svg" alt="webpack" width="40" height="40"/> </a> <a href="https://www.adobe.com/products/xd.html" target="_blank" rel="noreferrer"> <img src="https://cdn.worldvectorlogo.com/logos/adobe-xd.svg" alt="xd" width="40" height="40"/> </a> <a href="https://zapier.com" target="_blank" rel="noreferrer"> <img src="https://www.vectorlogo.zone/logos/zapier/zapier-icon.svg" alt="zapier" width="40" height="40"/> </a> </p>


<!---
Mr-vero/Mr-vero is a ✨ special ✨ repository because its `README.md` (this file) appears on your GitHub profile.
You can click the Preview link to take a look at your changes.
--->

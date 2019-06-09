[![Build Status](https://travis-ci.org/caepa/news.caepa.org.svg?branch=master)](https://travis-ci.org/caepa/news.caepa.org)


# news.caepa.org

Providing Colorado Leadership in Adult Education and Literacy since 1935

The Colorado Adult Education Professional Association, CAEPA, provides leadership to the field of adult education and family literacy by offering opportunities for professional development, advocacy, and resource sharing to improve the quality of life for every Coloradan.


---
Built with Material Components for the web

Material Components for the web (MDC Web) helps developers execute [Material Design](https://www.material.io).

How-to update CSS `assets/css/main.css`

**WATCH FOR BREAKING CHANGES**
[CHANGELOG: material-components-web](https://github.com/material-components/material-components-web/blob/master/CHANGELOG.md)

Check for outdated packages
```
npm update --save-dev
npm outdated
```

Update CSS packages
```
npm install normalize-scss@latest --save &&
npm install material-components-web@latest --save &&
npm start
```

Reset node_modules
```
rm -rf node_modules
npm install --save-dev
```

Reset and install dependencies as specified in ```package-lock.json``` only
```
npm ci
```

---
TODO:

  - [ ] Layout without drawer for self contained pages
  - [ ] Move subscribe form out of index
  - [ ] Improve form structure
  - [ ] Add staticman

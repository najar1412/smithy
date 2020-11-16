# Smithy
 
Smithy is a project to help me learn intermediate/advanced features of js/ts.
 
## Tech
 
Smithy is split across Python Django and JS/TS npm using webpack.
 
 * Python deals with the rest api and auth.
 * Javascript the frontend.
 
It feels very convoluted however its all little over my head to figure out.
Ultimately - considering how tight the js ecosystem is - its probably a good idea to phase out python/django in favour for js/express (or whatever the cool kids are using).
 
## Installation

 > IMP
 >
 > https://doc.babylonjs.com/guidedLearning/createAGame/gettingSetUp
 
## Dev

Start the Django api

```
cd smithy/
python manage.py runserver
```

Bundle Smithy and run webpack dev server

```
cd smithy/
npm run build
npm run start
```

## Production

 > IMP
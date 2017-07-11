# Embercamp 2017
A collection of links that cover what happened during EmberCamp 2017

### Photos

* To be released

### Live Blogs / Streams / Highlights

* None

### Talks

**Opening Keynote by [Matthew Beale](https://twitter.com/mixonic)**

- Slides: TBR
- Video: TBR
- Links
  - [Lighthouse](https://chrome.google.com/webstore/detail/lighthouse/blipmdconlkpinefehnmjammfjpmpbjk?hl=en)
  - [Glimmer: 201 Created](https://github.com/201-created/bodega-glimmer)
  - [Glimmer: Landed Module unification](https://github.com/emberjs/rfcs/blob/master/text/0143-module-unification.md)
  - [module-migrator](https://github.com/rwjblue/ember-module-migrator)
- Other information
  - Ember Module unification (Beta ember-cli 2.14+): `ember new <app-name> -b ember-module-unification-blueprint`

**Glimmer ✨ as a Gateway to Ember 🐹 by [Robert Jackson](https://twitter.com/rwjblue)**

- Slides: TBR
- Video: TBR
- Links
  - [Glimmer.js](https://glimmerjs.com/)
  - [ember-service-worker](https://github.com/DockYard/ember-service-worker)
  - [ember-service-worker-asset-cache](https://github.com/DockYard/ember-service-worker-asset-cache)
  - [ember-service-worker-cache-fallback](https://github.com/DockYard/ember-service-worker-cache-fallback)
  - [ember-web-app](https://github.com/san650/ember-web-app)
  - [ember-decorators](https://github.com/rwjblue/ember-decorators)
- Other information
  - Glimmer.js supports rollup treeshaking to minimise production builds
  - Glimmer.js with service workers gives a result of almost 100 on Lighthouse
  - Glimmer.js components in Ember apps is nearly a reality!

**Draw the line: stress-free coding standards by [Ingrid Epure](https://twitter.com/ingridepure)**

- Slides: TBR
- Video: TBR
- Links
  - [EmberConf 2017: Counter-spells and the Art of Keeping Your Application Safe by Ingrid Epure](https://www.youtube.com/watch?v=kPar8n9zaHo)
  - [AST Explorer](http://astexplorer.net/)
  - [ember-cli-detergent](https://www.npmjs.com/package/ember-cli-detergent)
- Other information
  - Disable style related rules in eslint for dev build time for developing code faster

**A FastBootable approach to D3-based graphing by [Kevin Kucharczyk](https://twitter.com/kevinkucharczyk)**

- Slides: TBR
- Video: TBR
- Links
  - [ember-d3](https://github.com/ivanvanderbyl/ember-d3)
  - [ember-sparkles](https://github.com/LocusEnergy/ember-sparkles)
  - [ember-d3-helpers](https://github.com/LocusEnergy/ember-d3-helpers)
  - [maximum-plaid](https://github.com/ivanvanderbyl/maximum-plaid)
  - [Generate charts in fastboot using Ember](https://github.com/ember-fastboot/ember-cli-fastboot/issues/105#issuecomment-187246877)
  - [Glimmer Regydration](https://github.com/glimmerjs/glimmer-vm/pull/549)

**Ember, more than the sum of its parts by [Ricardo Mendes](https://twitter.com/locks)**

- Slides: TBR
- Video: TBR
- Links
  - [New api docs website!](https://emberjs.com/api) & [Github](https://github.com/ember-learn/ember-api-docs)
  - [Making Ember.js Easier](https://emberjs.com/blog/2013/03/21/making-ember-easier.html)
  - [Be the bark](https://madhatted.com/2016/2/10/be-the-bark-ember-js-community)
  - [Ember Hearth](https://ember-hearth.readme.io/)
  - [Ember CLI addon docs](https://github.com/ember-learn/ember-cli-addon-docs)
  - [Ember Language server](https://github.com/emberwatch/ember-language-server)
- Other information
  - New ember learning team members! [Sivakumar kailasam](https://twitter.com/sivakumar_k)  [Terence Lee](https://twitter.com/hone02) 🙏
  - Road ahead
    - Restructuring guides to make it easier to find things
    - Provide support and material for creating your own workshops
    - Improvements on Ember API docs
    - Unify styleguides of all plugins & improve accessibility
    - New help wanted section

**Better Test selectors leveraging the complete Ember toolbelt by [Marco Otte-Witte](https://twitter.com/marcoow)**

- Slides: TBR
- Video: TBR
- Links
  - [ember-test-selectors](https://github.com/simplabs/ember-test-selectors)
  - [ember-test-selectors screencast](https://embermap.com/video/ember-test-selectors)
  - [Glimmer.js: ember-test-selectors support pending](https://github.com/simplabs/ember-test-selectors/issues/129)
- Other information
  - ember-test-selectors strip out `data-test` attributes from production builds to not increase bundle size

**Making Titanic Ember Apps Feel Tiny by [Marten Schilstra](https://twitter.com/Martndemus)**

- Slides: TBR
- Video: TBR
- Links
  - [use rel="preload" for loading stylesheets](http://caniuse.com/#search=preload), for full compatibility use [loadcss polyfill](https://github.com/filamentgroup/loadCSS)
  - [ember-service-worker - returning visitors](https://github.com/DockYard/ember-service-worker)
  - [PRPL](https://developers.google.com/web/fundamentals/performance/prpl-pattern/)
- Other information
  - Not recommended to use service-worker to cache api responses
    - Use IndexedDB to store api responses
  - Precache most common used modules
  - Lazy-load other modules using engines

**The Modern State of Web Components - A Glimmer of Hope by [Jessica Jordan](https://twitter.com/jjordan_dev)**

- Slides: TBR
- Video: TBR
- Links
  - (Webcomponents spec)[https://github.com/w3c/webcomponents]
  - [Webcomponents pollyfill available](https://github.com/webcomponents/webcomponentsjs)
  - [glimmer-poll example](https://github.com/jessica-jordan/glimmer-poll)
- Other information
  - Webcomponents spec could be used to integrate multiple frameworks React-Ember
  - Custom elements not supported by Edge
  - HTML import, only supported in Chrome
  - Glimmer.js supports creating a web component natively. `ember new <app-name> -b @glimmer/blueprint --web-component`
  - Promising API developments
    - HTML attributes for customisation (passing stringified JSON configuration to components)
    - HTML imports for distributing Glimmer.js components (using rel="import")
    - Styles in ShadowDOM or as co-located CSS
    - Testing for Glimmer.js apps
    - `<slot></slot>` API for "yielding" component content

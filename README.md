# Orion

Orion is an open source framework built on Meteor that makes complex as well as simple apps possible with minimal effort. It's built, modified, used, and supported by an active community of people around the world.

[![paypal](https://www.paypalobjects.com/en_US/i/btn/btn_donate_LG.gif)](https://www.paypal.com/cgi-bin/webscr?cmd=_s-xclick&hosted_button_id=4RJ7GP2UST4EN)

## Getting Started

To start your orion instance the first thing you need to do is install the core package, a admin template and a router.

```sh
meteor add orionjs:core
```

#### Install a template

Orion has two official templates, one for [bootstrap](http://getbootstrap.com) and one for [materialize](http://materializecss.com), but you can use one in the list below

**Bootstrap:**

```sh
meteor add twbs:bootstrap fortawesome:fontawesome orionjs:bootstrap
```

**Materialize:**

```sh
meteor add materialize:materialize orionjs:materialize
```

#### Install a router

Orion supports [iron:router](https://github.com/iron-meteor/iron-router) and [kadira:flow-router](https://github.com/kadirahq/flow-router) thanks to [nicolaslopezj:router-layer](https://github.com/nicolaslopezj/meteor-router-layer).

**iron:router:**

```sh
meteor add iron:router
```
**kadira:flow-router:**

```sh
meteor add kadira:flow-router kadira:blaze-layout
```

#### Start using Orion

```sh
meteor
```

And go

[http://localhost:3000/admin](http://localhost:3000/admin)


## Links

- **Website:** [orionjs.org](http://orionjs.org)
- **Documentation:** [docs.orionjs.org](http://docs.orionjs.org/)
- **Tutorials:** [orionjs.org/tutorials](http://orionjs.org/tutorials)
- **Forums:** [forums.orionjs.org](http://forums.orionjs.org)
- **Gitter:** [gitter.im/orionjs/orion](https://gitter.im/orionjs/orion)
- **Preview:** [orion-example.meteor.com](http://orion-example.meteor.com)
- **Roadmap:** [trello.com/b/dQhi5dF9/orion-roadmap](https://trello.com/b/dQhi5dF9/orion-roadmap)

### Translate Orion

If you want to help translating Orion to your language follow the [instructions](https://github.com/orionjs/examples/tree/master/language).

## Made With Orion

- [franciscainfante.com](http://franciscainfante.com?utm_source=orion-madeby&utm_medium=orion-github&utm_campaign=orion-madeby) - [Source](https://github.com/madeby-nicolaslopezj/fran2)
- [weeshing.com](http://weeshing.com?utm_source=orion-madeby&utm_medium=orion-github&utm_campaign=orion-madeby)

Feel free to add your made with Orion site doing a pull request.


## Community Add-On Packages

*Submit a pull request to add your package to this list*

**Admin Themes:**

- [rwatts:orionjs-foundation](https://github.com/rwatts3/orionjs-contrib/tree/orionjs-foundation)
- [dvz:orion-semantic-ui](https://github.com/amazingBastard/orion-semantic-ui)
- [dvz:orion-unstyled](https://github.com/amazingBastard/orion-unstyled)
- [nicolaslopezj:orion-admin-only-bootstrap](https://github.com/nicolaslopezj/orion-admin-only-bootstrap) use bootstrap theme without using bootstrap in the whole app

**Attributes:**

- [rwatts:orion-maps](https://atmospherejs.com/rwatts/orion-maps)
- [nicolaslopezj:orion-users-with-roles-attribute](https://github.com/nicolaslopezj/orion-users-with-roles-attribute) Users relationship with roles filter
- [dvc:orion-tags](https://github.com/dvc94ch/orion-tags/) Bootstrap tags input
- [nicolaslopezj:orion-rut-input](https://github.com/nicolaslopezj/orion-rut-input) Rut input (Chile)

**Filesystem:**

- [vsivsi:orion-file-collection](https://atmospherejs.com/vsivsi/orion-file-collection) Lightweight MongoDB gridFS support
- [lc3t35:orion-filesystem-local](https://github.com/lc3t35/orion-filesystem-local)
- [brightbind:orion-gridfs](https://github.com/brightbind/orion-gridFS/)
- [rwatts:orionjs-cloudinary](https://atmospherejs.com/rwatts/orionjs-cloudinary)

**Languages:**

- [tunifight:orion-lang-ar](https://github.com/nabiltntn/orion-lang-ar.git) Arabic
- [findegil:orion-lang-bg](https://atmospherejs.com/findegil/orion-lang-bg) Bulgarian
- [loongmxbt:orion-lang-zh-cn](https://github.com/loongmxbt/orion-lang-zh-cn) Chinese Simplified
- [jorisroling:orion-lang-nl](https://github.com/jorisroling/orion-lang-nl) Dutch
- [pierreeric:orion-lang-fr](https://atmospherejs.com/pierreeric/orion-lang-fr) French
- [budickda:orion-lang-de](https://atmospherejs.com/budickda/orion-lang-de) German
- [palpinter:orion-lang-hu](https://github.com/palpinter/orion-lang-hu.git) Hungarian
- [aselox:orion-lang-it](https://atmospherejs.com/aselox/orion-lang-it) Italian
- [brajt:orion-lang-pl](https://github.com/brajt/orion-lang-pl) Polish
- [goooseman:orion-lang-ru](https://github.com/goooseman/orion-lang-ru) Russian
- [eyeskiller:orion-lang-sk](https://github.com/eyeskiller/orion-lang-sk) Slovak
- [orionjs:lang-es](https://github.com/orionjs/orion/tree/master/packages/lang-es) Spanish

**Integrations:**

- [nicolaslopezj:orion-ga](https://github.com/nicolaslopezj/orion-ga) Google analytics
- [rwatts:orionjs-gtm](https://atmospherejs.com/rwatts/orionjs-gtm) Google Tag Manager

**Others:**

- [nicolaslopezj:orion-exporter](https://github.com/nicolaslopezj/orion-exporter) Export and import Orion data
- [rwatts:orionjs-dashboard](https://atmospherejs.com/rwatts/orionjs-dashboard) Add a Dashboard & Widgets to Orion

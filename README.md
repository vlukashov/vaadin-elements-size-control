# Vaadin Components Size Control

The table below shows the impact (in kB) that adding a single [Vaadin Component](https://vaadin.com/components) would have onto the effective app bundle size. It depends on whether or not the application already uses the [Polymer 2](https://www.polymer-project.org/) library (and if it does, then how much of Polymer is already in use). In addition to Vaadin Components, some Paper Elements are listed as well for comparison.

## Impact (version v10.0.0-beta4)

| Component                     | full Polymer in app | some Polymer in app | no Polymer in app |
| ----------------------------- | ------------------- | ------------------- | ----------------- |
| [vaadin-board][09]            | 8.8 kB              | 43.5 kB             | 110.3 kB          |
| [vaadin-button][10]           | 22.2 kB             | 25.7 kB             | 78 kB             |
| [paper-button][01]            | 38.7 kB             | 73.4 kB             | 140.2 kB          |
| [vaadin-charts][11]           | 401.5 kB            | 436.1 kB            | 503 kB            |
| [vaadin-checkbox][12]         | 17.5 kB             | 21 kB               | 73.3 kB           |
| [paper-checkbox][02]          | 44.3 kB             | 79 kB               | 145.8 kB          |
| [vaadin-combo-box][13]        | 109.7 kB            | 144.4 kB            | 211.2 kB          |
| [vaadin-context-menu][14]     | 32.5 kB             | 67.1 kB             | 134 kB            |
| [vaadin-core][15]             | 622.9 kB            | 657.6 kB            | 724.4 kB          |
| [vaadin-date-picker][16]      | 111.2 kB            | 145.9 kB            | 212.7 kB          |
| [vaadin-dialog][17]           | 25.1 kB             | 59.8 kB             | 126.6 kB          |
| [paper-dialog][03]            | 57.9 kB             | 92.6 kB             | 159.4 kB          |
| [vaadin-dropdown-menu][18]    | 68.1 kB             | 102.8 kB            | 169.6 kB          |
| [paper-dropdown-menu][04]     | 109.2 kB            | 143.8 kB            | 210.7 kB          |
| [vaadin-form-layout][19]      | 21 kB               | 55.6 kB             | 122.5 kB          |
| [vaadin-grid][20]             | 154.2 kB            | 188.9 kB            | 255.7 kB          |
| [vaadin-icons][21]            | 245.5 kB            | 280.2 kB            | 347.1 kB          |
| [vaadin-item][22]             | 14.4 kB             | 17.2 kB             | 59 kB             |
| [vaadin-list-box][23]         | 14.7 kB             | 23.1 kB             | 64.9 kB           |
| [vaadin-notification][24]     | 19.7 kB             | 23.2 kB             | 70 kB             |
| [vaadin-ordered-layout][25]   | 5.7 kB              | 8.5 kB              | 50.3 kB           |
| vaadin-pro                    | 408.3 kB            | 443 kB              | 509.8 kB          |
| [vaadin-progress-bar][27]     | 15 kB               | 18.5 kB             | 60.3 kB           |
| [paper-progress][06]          | 24 kB               | 58.6 kB             | 125.5 kB          |
| [vaadin-radio-button][28]     | 18.8 kB             | 26.7 kB             | 79 kB             |
| [paper-radio-button][07]      | 56.1 kB             | 90.8 kB             | 157.6 kB          |
| [vaadin-split-layout][29]     | 17.5 kB             | 52.1 kB             | 119 kB            |
| [vaadin-tabs][30]             | 35 kB               | 69.7 kB             | 136.5 kB          |
| [paper-tabs][08]              | 66.2 kB             | 100.9 kB            | 167.7 kB          |
| [vaadin-text-field][31.1]     | 26.8 kB             | 30.3 kB             | 72.1 kB           |
| [paper-input][05]             | 49.8 kB             | 84.5 kB             | 151.3 kB          |
| [vaadin-password-field][31.2] | 37.8 kB             | 41.2 kB             | 83.1 kB           |
| [vaadin-text-area][31.3]      | 30.3 kB             | 33.8 kB             | 75.6 kB           |
| [vaadin-upload][32]           | 50.7 kB             | 54.2 kB             | 118.4 kB          |

[01]: https://github.com/PolymerElements/paper-button "see the <paper-button> repo on GitHub"
[02]: https://github.com/PolymerElements/paper-checkbox "see the <paper-checkbox> repo on GitHub"
[03]: https://github.com/PolymerElements/paper-dialog "see the <paper-dialog> repo on GitHub"
[04]: https://github.com/PolymerElements/paper-dropdown-menu "see the <paper-dropdown-menu> repo on GitHub"
[05]: https://github.com/PolymerElements/paper-input "see the <paper-input> repo on GitHub"
[06]: https://github.com/PolymerElements/paper-progress "see the <paper-progress> repo on GitHub"
[07]: https://github.com/PolymerElements/paper-radio-button "see the <paper-radio-button> repo on GitHub"
[08]: https://github.com/PolymerElements/paper-tabs "see the <paper-tabs> repo on GitHub"
[09]: https://github.com/vaadin/vaadin-board "see the <vaadin-board> repo on GitHub"
[10]: https://github.com/vaadin/vaadin-button "see the <vaadin-button> repo on GitHub"
[11]: https://github.com/vaadin/vaadin-charts "see the <vaadin-charts> repo on GitHub"
[12]: https://github.com/vaadin/vaadin-checkbox "see the <vaadin-checkbox> repo on GitHub"
[13]: https://github.com/vaadin/vaadin-combo-box "see the <vaadin-combo-box> repo on GitHub"
[14]: https://github.com/vaadin/vaadin-context-menu "see the <vaadin-context-menu> repo on GitHub"
[15]: https://github.com/vaadin/vaadin-core "see the <vaadin-core> repo on GitHub"
[16]: https://github.com/vaadin/vaadin-date-picker "see the <vaadin-date-picker> repo on GitHub"
[17]: https://github.com/vaadin/vaadin-dialog "see the <vaadin-dialog> repo on GitHub"
[18]: https://github.com/vaadin/vaadin-dropdown-menu "see the <vaadin-dropdown-menu> repo on GitHub"
[19]: https://github.com/vaadin/vaadin-form-layout "see the <vaadin-form-layout> repo on GitHub"
[20]: https://github.com/vaadin/vaadin-grid "see the <vaadin-grid> repo on GitHub"
[21]: https://github.com/vaadin/vaadin-icons "see the <vaadin-icons> repo on GitHub"
[22]: https://github.com/vaadin/vaadin-item "see the <vaadin-item> repo on GitHub"
[23]: https://github.com/vaadin/vaadin-list-box "see the <vaadin-list-box> repo on GitHub"
[24]: https://github.com/vaadin/vaadin-notification "see the <vaadin-notification> repo on GitHub"
[25]: https://github.com/vaadin/vaadin-ordered-layout "see the <vaadin-ordered-layout> repo on GitHub"
[27]: https://github.com/vaadin/vaadin-progress-bar "see the <vaadin-progress-bar> repo on GitHub"
[28]: https://github.com/vaadin/vaadin-radio-button "see the <vaadin-radio-button> repo on GitHub"
[29]: https://github.com/vaadin/vaadin-split-layout "see the <vaadin-split-layout> repo on GitHub"
[30]: https://github.com/vaadin/vaadin-tabs "see the <vaadin-tabs> repo on GitHub"
[31.1]: https://github.com/vaadin/vaadin-text-field "see the <vaadin-text-field> repo on GitHub"
[31.2]: https://github.com/vaadin/vaadin-text-field "see the <vaadin-password-field> repo on GitHub"
[31.3]: https://github.com/vaadin/vaadin-text-field "see the <vaadin-text-area> repo on GitHub"
[32]: https://github.com/vaadin/vaadin-upload "see the <vaadin-upload> repo on GitHub"

_(last updated on March 31st, 2018)_

## What is measured and how

The numbers in the table show how much the application bundle size will increase after importing a single Vaadin Component. This assumes that the application is built with the [Polymer CLI](https://www.polymer-project.org/2.0/docs/tools/polymer-cli) which is the recommended way for Polymer projects. All imports are bundled and minified, but not transpiled into ES5.

Each row in the table has three numbers:

* **full Polymer in app**: size impact for an app that already uses the _entire_ Polymer 2 library

  In this scenario no dependencies that a component might have to the Polymer 2 library are counted into its impact.

* **some Polymer in app**: size impact for an app that uses the most common parts of the Polymer 2 library

  In this scenario some Polymer 2 dependencies are counted into the component size impact, and some are excluded. See the list of the excluded dependencies in the `app-shell-some-polymer.html` file.

* **no Polymer in app**: size impact for an app that does not use the Polymer 2 library

  This scenario shows the size impact of including a Vaadin Component into a non-Polymer application. All dependencies that a component has to the Polymer 2 library are counted into its size impact.

All numbers are in kilobytes (1 kB = 1000 bytes). The [polyfills](https://github.com/webcomponents/webcomponentsjs) for the Web Components APIs are not included into the measurement.

## Running the measurements locally

* clone the repo: `git clone https://github.com/vlukashov/vaadin-components-size-control.git`
* install NPM and Bower dependencies: `npm install`
* run the `size-control` npm script: `npm run size-control`

## Why to run locally?

* verify the results
* measure the size impact of a different version of a component
* measure the size impact for an app that uses a different subset of Polymer 2 features
* measure the combined impact of a set of Vaadin Components
* measure the size impact of another Polymer element

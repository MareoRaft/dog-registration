Angular seems quite nice.  Let's build it as an angular app, so it can work also nicely on phones/small screens.

let's use formly for angular 2+:
https://github.com/formly-js/ngx-formly

this looks nice:
https://ngx-bootstrap-latest.surge.sh/#/

bootstrap themes w forms:
https://demos.creative-tim.com/argon-design-system/index
NOT UP TO DATE:
https://github.com/formly-js/angular-formly-templates-bootstrap
https://alligator.io/angular/formly/

the next step is to add our images of dogs.  Then we can throw it up on GitHub.

the next step is to get bootstrap-formly properly configured.  Currently we have bootstrap, but we haven't hooked the css up to formly fully, so certain things like drop-downs are not normalized.

gameplan:
argon works, although it's annoying that the scss files have to sit in the src directory.  Perhaps that can be fixed.

but the DROPDOWN css still does not.  So let's try:
angular-formly-templates-bootstrap







Optional:
file upload
disable or hide fields

Formly links to all the formly form builders
https://github.com/formly-js

angular-Formly is for angular.  It has a bunch of examples on the left column:
http://angular-formly.com/#!/
features:
input -- yes
paragraph input -- yes
drop down -- yes
drop down with search
radio button (use drop down)
validate inputs with useful error messages next to the inputted thing -- yes
checkbox -- yes
file upload -- plugin
disable or hide fields -- yes

Vue-formly is basically the same thing but for Vue.js
https://github.com/formly-js/vue-formly

jQuery formbuilder: seems quite nice
https://formbuilder.online
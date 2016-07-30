Standalone Interactive Exercise: Speech Assessment
==========

##### About swallow assessment
Infographic to explore age-specific behaviors warranting a swallow assessment

##### About Multidisciplinary Approaches to Children’s Oral Health (MATCH)
There are a variety of healing and helping professions that, when partnered with pediatric dentists, hold tremendous potential to improve children’s oral health and welfare.

Since many factors contribute to good oral health in children—social, behavioral, genetic, nutritional, dental care, and education, engaging experts in these various fields can both help reduce disease occurrence and improve quality of care.

These modules are developed with support from the Health Resources and Services Administration Title VII Training Grant D88HP20109 on Building a sustainable network of pediatric dentists committed to care of underserved children. In recognition of this, faculty at the Columbia University College of Dental Medicine and the Columbia University Center for New Media Teaching and Learning (CCNMTL) have developed these comprehensive online modules which aim to:

Highlight non-dental professions that can impact children’s oral health
Suggest ways pediatric dentists can partner with them most effectively to enhance practice success
Present examples of successful pediatric dentists who enhance their patient care through partnerships with these professions

REQUIREMENTS
------------
npm

DEV INSTALLATION
------------
1. Clone the repository
2. Type make runserver. This command will install the necessary npm modules, build the bundle and spin up Webpack's dev server.
3. Navigate to http://localhost:8080.
4. Play around with the interactive!

NPM INSTALLATION
------------
1. npm install swallowassessment-pack
2. ./node_modules/webpack/webpack.js --output-path <output_path> --config ./node_modules/swallowassessment-pack/webpack.config.js
3. Embed the interactive via an iframe.


```
<code>
    <iframe src="<server>/<output_path>/"></iframe>
</code>
```

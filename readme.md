<div align="center">
	<h1>Constyble continuous integration example</h1>
	<p>This repository demonstrates how to use Constyble in a project as described in <a href="https://www.projectwallace.com/blog/integrating-constyble-into-ci-workflow/">this blog post</a>.</p>
</div>


## Key points

* `package.json` containing the `constyble` devDependency and `npm test` script
* `.constyblerc` containing the thresholds configuration to test
* `styles/main.css` with the CSS that will be tested
* `.travis.yml` to make sure that every Pull Request and branch push will be `npm test`ed

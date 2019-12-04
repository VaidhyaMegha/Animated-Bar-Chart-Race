
# Bar Chart Race, Explained

The bar chart race is an animated chart and it displays top "n" values as per year or any category.It will take 2 or 3 mins to generate bar chart.Please wait.

https://observablehq.com/@d3/bar-chart-race-explained@3007

View this notebook in your browser by running a web server in this folder. For
example:

~~~sh
python -m SimpleHTTPServer
~~~

Or, use the [Observable Runtime](https://github.com/observablehq/runtime) to
import this module directly into your application. To npm install:

~~~sh
npm install @observablehq/runtime@4
npm install https://api.observablehq.com/@d3/bar-chart-race-explained.tgz?v=3
~~~

Then, import your notebook and the runtime as:

~~~js
import {Runtime, Inspector} from "@observablehq/runtime";
import define from "@d3/bar-chart-race-explained";
~~~

To log the value of the cell named “foo”:

~~~js
const runtime = new Runtime();
const main = runtime.module(define);
main.value("foo").then(value => console.log(value));
~~~
=======



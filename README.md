# FlexBenchmark

This is just a performance comparison of [@angular/flex-layout](https://github.com/angular/flex-layout) with 1000 nodes and 5 divs per Node.

Install deps:

`yarn`

Start server:

`yarn start`

Then run your own tests. There are two branches here. `using-lib` and `without-using-lib`

One uses the flex directives, and the other uses just CSS (SCSS). 

With pure CSS is about 5 times faster and reduces the scripting time from 4 seconds to 0.7 seconds, in my machine with no throttling, browser in guest mode.

## License 

MIT

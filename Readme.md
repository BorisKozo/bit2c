# bit2c
A node.js module for accessing bit2c (the israeli bitcoin echange) API.

## Installing

clone the lib, cd to its root path and then:

<pre><code>
npm install
</code></pre>


## running the tests
If you want to run the tests that require access to the private API you should define 2 environment variables:
* BIT2C_KEY - your bit2c key
* BIT2C_SECRET - your bit2c key

Warning - these keys grant access to your bit2c account! keep them safe!

For running the tests just use:
<pre><code>
npm test
</code></pre>

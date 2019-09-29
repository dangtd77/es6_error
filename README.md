# es6_error
 error Uncaught TypeError: Cannot read property 'call' of undefined

I'm getting the following error in the console when trying to perform the first part of the import/export of the fellowship

also adding without the node modules

bundle.js:20 Uncaught TypeError: Cannot read property 'call' of undefined
    at __webpack_require__ (bundle.js:20)
    at eval (index.js:3)
    at Object../app/index.js (bundle.js:97)
    at __webpack_require__ (bundle.js:20)
    at eval (webpack:///multi_(:3000/webpack)-dev-server/client?:2:18)
    at Object.0 (bundle.js:468)
    at __webpack_require__ (bundle.js:20)
    at bundle.js:84
    at bundle.js:87
__webpack_require__	@	bundle.js:20
eval	@	index.js:3
./app/index.js	@	bundle.js:97
__webpack_require__	@	bundle.js:20
eval	@	client:2
0	@	bundle.js:468
__webpack_require__	@	bundle.js:20
(anonymous)	@	bundle.js:84
(anonymous)	@	bundle.js:87

# timer-module
Timer module for the website

To run the module, you need to write the deadline in the script.js file (In the 6th line), the functionality of the module is in the timer.js file !

You can run the index.html file to see an example


#example

import timer from './modules/timer';

window.addEventListener('DOMContentLoaded', function() {
    timer('.timer', '2021-03-21');
});

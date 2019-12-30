# UltimateDebounce
Debouncing Library based on Article by Elliot Williams: DEBOUNCE YOUR NOISY BUTTONS, From Dec. 10, 2015
    https://hackaday.com/2015/12/10/embed-with-elliot-debounce-your-noisy-buttons-part-ii/#more-180185
    
Library writting for Arduino do simply and effectively debounce button, based on the article and example referenced above.

This version Also allows the user to Select if a signal is Active High or Active Low.

'ObjectName'.update();   Must be run frequently.   
    Suggest to run once per loop, or on Timer interrupt with Flags for Pressing & releasing events.

This code is still in development, but seems to work fine for 8-bit / cycle implementations.

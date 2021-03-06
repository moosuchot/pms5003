# Compatibility with other sensors

## [Plantover](http://www.plantower.com)

For most [Plantover](http://www.plantower.com) sensors probably it is an easy task to add support

| Sensor     | verified                   | Compatibility           | Note                                                                      |
|------------|----------------------------|-------------------------|---------------------------------------------------------------------------|
| PMS 1003   | Documentation not reviewed | Expected it should work | https://at7.pl/komunikacja-plantower-pms1003-pms3003/                   |
| PMS 3003   | Documentation reviewed     | It will not work        | Shorter data frame                                                        |
| PMS 3003P  | Documentation not reviewed | I have no idea          | Shorter data, PWM output not supported                                    |
| **PMS 5003**   | **Tested**                     | **It works fine**           |                                                                           |
| PMS 5003P  | Documentation not reviewed | I have no idea          | PWM not supported                                                         |
| PMS 5003T  | Documentation reviewed     | It will not work        | Longer data frame                                                         |
| PMS 5003ST | Documentation reviewed     | It will not work        | Longer data frame                                                         |
| PMS 5003I  | Documentation not reviewed | It will not work        | I2C communication not supported                                           |
| PMS 6003   | Documentation not reviewed | Expected it should work |                                                                           |
| PMS 6003P  | Documentation not reviewed | I have no idea          | PWM not supported                                                         |
| PMS 7003   | Documentation reviewed     | Expected it should work | Reserved word contains version number and error code, pinout is different |
| PMS 7003P  | Documentation not reviewed | I have no idea          | Reserved word contains version number and error code, PWM not supported   |
| PMS 7003I  | Documentation not reviewed | It will not work        | I2C communication not supported                                           |
| PMS 7003M  | Documentation not reviewed | I have no idea          |                                                                           |
| PMS A003   | Documentation not reviewed | I have no idea          |                                                                           |
| PMS A003P  | Documentation not reviewed | I have no idea          | PWM not supported                                                         |
| PMS A003I  | Documentation not reviewed | I have no idea          | I2C communication not supported                                           |

## Other

Probably other sensors are not compatible with PM5003 library.

If you are interested in adding support for your sensor: feel free to ask.

---

![Plantover sensors](https://github.com/jbanaszczyk/pms5003/blob/master/doc/PMSx003_PLANTOWER.jpg)




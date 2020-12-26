A hat with an RTC, so crystal, and what else? Some attempts add an I2C circuit, so that it's easy to communicate with the Zero. So long for the RTC that does exist in the H3, but that is not wired anywhere.
The status of the RTC on the Zero is not really [clear](https://forum.armbian.com/topic/13137-orange-pi-zero-internal-rtc/) to me.
We should maybe have a look at [this documentation](https://epsilonrt.fr/2020/01/rtc-armbian/?doing_wp_cron=1608288451.0372149944305419921875).
Sorry, it's in french.

Could there be a configuration item so that we're able to send the RTC to other boards via I2C?

Regarding your [comment](https://github.com/Thore-Krug/awesome-addon-boards/pull/1#pullrequestreview-555980992) Thore, let's go with internal temperature compensated crystal, as it's not available in through hole variants.

Is the use of a RTC IC with a External Crystal OK or would a Internal temperature compensated Crystal be prefered ? ( No ICs with a External crystal are available in through hole variants )

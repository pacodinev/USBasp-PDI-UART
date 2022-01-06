This is a merge of two repositories with some fixes on main ISP function of USBasp

main: https://www.fischl.de/usbasp/

USBASP-PDI: https://github.com/nieldk/USBASP-PDI

usbasp-uart: https://github.com/akrasuski1/usbasp-uart

I added a function to automatically find best (highest) SCK speed,
Plus added an extra reset delay for retries to make a better communication
on boards with high RC values on RST pin. (In my cases, I have a lot!)


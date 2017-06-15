![Unicorn HAT HD](unicorn-hat-logo.png)
http://shop.pimoroni.com/products/unicorn-hat-hd 

## Installing

### Full install (recommended):

We've created an easy installation script that will install all pre-requisites and get your Unicorn HAT HD
up and running with minimal efforts. To run it, fire up Terminal which you'll find in Menu -> Accessories -> Terminal
on your Raspberry Pi desktop, as illustrated below:

![Finding the terminal](http://get.pimoroni.com/resources/github-repo-terminal.png)

In the new terminal window type the command exactly as it appears below (check for typos) and follow the on-screen instructions:

```bash
curl https://get.pimoroni.com/unicornhathd | bash
```

If you choose to download examples you'll find them in `/home/pi/Pimoroni/unicornhathd/`.

### Manual install:

#### Library install for Python 3:

```bash
sudo apt-get install python3-pip python3-dev
sudo pip3 install unicornhathd
```

#### Library install for Python 2:

```bash
sudo apt-get install python-pip python-dev
sudo pip install unicornhathd
```

### Development:

If you want to contribute, or like living on the edge of your seat by having the latest code, you should clone this repository, `cd` to the library directory, and run:

```bash
sudo apt-get install python-dev python-setuptools
sudo python3 setup.py install
```
(or `sudo python setup.py install` whichever your primary Python environment may be)

In all cases you will have to enable the i2c bus.

## Documentation & Support

* Guides and tutorials - https://learn.pimoroni.com/unicorn-hat-hd
* Function reference - http://docs.pimoroni.com/unicornhathd/
* GPIO Pinout - http://pinout.xyz/pinout/unicorn_hat_hd
* Get help - http://forums.pimoroni.com/c/support
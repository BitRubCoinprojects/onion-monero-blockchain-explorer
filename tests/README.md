## Python selenium testing of the explorer

As the explorer grows, Monero keep changing, it is increasingly time consuming
to keep testing the explorer manually. Thus, with the help of selenium, python and nose
it is hoped that, at least part, of this process can be automated.

#### Install dependencies in Arch Linux

```bash
sudo pacman -S python-selenium python-nose geckodriver
```

#### Run the tests

```
nosetests main.py
```
# Programming with Clac

Now that you have written a fully functional Clac implementation it is time to put it to use. Below are a list of problems to solve with clac:

* Count number of digits in number (digits)
* Temperature converter
	* Degree to Celcius (fah2cel)
	* Celcius to Degrees (cel2fah)
* Bit Shift
	* Left (leftshift)
	* Right (rightshift)

* Determine if given year is a leap year (leapyear)
* Print the first n fibonnaci numbers (n fib)
* Convert Binary to Decimal (bin2dec)

##### The ClacRunner has been modified to allow clac code to be run from .clac files.

A program.clac file:
```clac
: square 2 ** ;
2 square
```
How to run:

```bash
java ClacRunner program
```

The output:

```clac
stack] 4
clac>> square
stack] 16
clac>>
```

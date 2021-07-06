# Confessions Script

This script allows the user to view any of the following in their command line:
* The Apostles Creed
* The Nicene Creed
* The Athanasian Creed
* Westminster Shorter Catechism (any Q&A, 1-107)
* Westminster Larger Catechism (any Q&A, 1-196)

## Setup

1. Clone this git repo in your preferred script folder.

`git clone https://github.com/bctgit/confessions_script.git`

2. Add the confessions directory into $PATH to be able to access this script from anywhere. I added the following to /home/bryan/.bashrc

`export PATH="/home/bryan/scripts/confessions:$PATH"`

## Flags

**-a**
	Apostles Creed, takes no arguments

**-n**
	Nicene Creed, takes no arguments

**-t**
	Athanasian Creed, takes no arguments

**-s**
	Shorter Catechism, argument = number between 1 and 107

**-l**
	Larger Catechism, argument = number between 1 and 196

## Examples

**Input:**

`confess -s 1`

**Output:**

Q. 1. What is the chief end of man?
A. Man's chief end is to glorify God, and to enjoy him forever.

**Input:**

`confess -l 162`

**Output:**

Q. 162. What is a sacrament?
A. A sacrament is an holy ordinance...

**Input:**

`confess -a`

**Output:**

I believe in God the Father Almighty,
  Maker of heaven and earth...

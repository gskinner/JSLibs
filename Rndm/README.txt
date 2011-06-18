** Rndm **
Provides simple methods for working with random values, such as Rnd.float(min, max), and Rnd.sign(). Also includes a seeded random version, Rndm.

There are three versions of the Rnd class included:

Rnd - uses Math.random() as it's generator. Not seeded. Recommended for most uses.

Rndm - seeded pseudo-random numbers. Generally adequate for games / experiments, but not more critical uses.

ex.
if (Math.boolean(0.2)) {
	foo.x = Math.sign()*Math.float(20,40);
}
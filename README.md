GoldCoin (GLD) - an improved version of Litecoin using scrypt as a proof of work scheme.
 - 2.5 minute block targets up till block 35000
 - 2 minute block targets there after
 - 504 blocks per difficulty retarget up to block 35000
 - 60 blocks per difficulty retarget thereafter

Block rewards in order:

 - 200 Block @ 10000 GLD
 - 2000	Blocks @ 1000 GLD
 - 24000 Blocks @ 500 GLD
 - (The values below are post-fork in development/dispute values)
 - 262800 Blocks @ 400 GLD
 - ... (Reduce by 8 every 2 years)
 - 262800 Blocks @ 8 GLD
 - Total Blocks: 26315000 (not final)
 - The default ports are 8121 (connect) and 8122 (fson rpc)

Notice the block fork number showed in this release is not necessarily the correct one.

If you wish to use this code anyways, be sure to increase the blockFork number accordingly to a very large
value until the fork is actually announced. Otherwise you may run into problems.

Don't say we didn't warn you :) (PS. Its the variable julyFork in the main.h file)


Development process
===================

Developers work in their own trees, then submit pull requests when
they think their feature or bug fix is ready.

The patch will be accepted if there is broad consensus that it is a
good thing.  Developers should expect to rework and resubmit patches
if they don't match the project's coding conventions (see coding.txt)
or are controversial.

The master branch is regularly built and tested, but is not guaranteed
to be completely stable. Tags are regularly created to indicate new
official, stable release versions of Goldcoin.

Feature branches are created when there are major new features being
worked on by several people.

From time to time a pull request will become outdated. If this occurs, and
the pull is no longer automatically mergeable; a comment on the pull will
be used to issue a warning of closure. The pull will be closed 15 days
after the warning if action is not taken by the author. Pull requests closed
in this manner will have their corresponding issue labeled 'stagnant'.

Issues with no commits will be given a similar warning, and closed after
15 days from their last activity. Issues closed in this manner will be 
labeled 'stale'. 

Check out http://gldcoin.com for more info about the development.

Development Team
================
- akumaburn
- Stouse49

Consultants
================
- Sting17
- Microguy
- AZIZ1977


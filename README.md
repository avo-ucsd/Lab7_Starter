# Lab 7
Ashley Vo

## Intro
1.  Automated testing should be **(1) within a GitHub action whenever code is pushed**. The reason for this is because the tests can run on all branches, so if a team is working on multiple branches for a Recipe project, then the team has a universal and uniform source of tests. Additionally, this is an automated process- no manual work needs to be done other than checking up on a test to see the details should a fail occur. This is good for a couple of reasons: 1) developer time isn't wasted running tests or trying to make sure all tests were run correctly 2) if more tests are added, the team could add it to the testing pipeline rather than updating the team that changes were made 3) the team can have protection rules on GitHub to only allow merges that passed all tests. This ensures the code is meeting certain standards *during* development.

## Expose
2.  No. 

## Explore
3. Navigation tests the performance from loading and how well a user could move through the site. On the other hand, Snapshot mode looks at the page and DOM "as-is" (i.e. at the time of testing).

4. (1) The JavaScript could be minified to reduce and save on memory. (2) Images could be reduced in size to reduce load times (this is especially helpful when data/networks are limited for a user). (3) Other image formats (WebP and AVIF) have better compression and thus don't take up as much data as PNGs or JPEGs.
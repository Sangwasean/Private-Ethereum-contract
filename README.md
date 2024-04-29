Part 1: Install Blockchain Required Tools
-truffle(npm install -g truffle)
Part 2. Use following command to build:
(truffle compile)
Part 3: Create migration file using following command
(truffle create migration HelloWorld)
Part 4:Run
(truffle develop)
Part 5:Run
(truffle migrate)
Part 6:Run line by line
-truffle console
-let instance = await HelloWorld.deployed()
-instance.getMessage()



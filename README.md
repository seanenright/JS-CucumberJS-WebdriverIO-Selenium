# Setup
```
	export SAUCE_USERNAME=your_username
	export SAUCE_ACCESS_KEY=your_access_key
	npm install -g grunt-cli
	npm install
```

# Running tests
to run all tests in parallel (i.e. in build):
```
	grunt
```

to run single single test (feature):
```
	./node_modules/.bin/cucumber.js features/homepage.feature
```

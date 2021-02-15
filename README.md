git submodule add -f -- https://github.com/shinehlina/test-repo src/test


Если у вас есть права на test, но чет ничего не подтягивается и не аутентифицируется
`git submodule init`

`git config submodule.src/test.url https://{username}:{password}@github.com/shinehlina/test-repo`

`git submodule update`

По надобности - reimport мавена
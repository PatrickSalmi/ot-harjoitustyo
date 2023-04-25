# Tower defence game

[Release](https://github.com/PatrickSalmi/Tower-defence-game/releases/tag/viikko5)

## Documentation
[Requirements specifications](https://github.com/PatrickSalmi/Tower-defence-game/blob/master/documentation/requirements_specifications.md)

[Architecture](https://github.com/PatrickSalmi/Tower-defence-game/blob/master/documentation/architecture.md)

[Work time log](https://github.com/PatrickSalmi/Tower-defence-game/blob/master/documentation/work_time_log.md)

[Changelog](https://github.com/PatrickSalmi/Tower-defence-game/blob/master/documentation/changelog.md)

## Command line operations

Install dependencies with the command:
```
poetry install
```
Start the game with the command:
```
poetry run invoke start
```
### Testing

Run tests with the command:
```
poetry run invoke test
```
### Test coverage

The test coverage report can be generated with the command:
```
poetry run invoke coverage-report
```
The report is generated in the *htmlcov* directory.

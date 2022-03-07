# Wait / Sleep action

[![Action test on Ubuntu](https://github.com/GuillaumeFalourd/wait-sleep-action/actions/workflows/ubuntu_action_test.yml/badge.svg)](https://github.com/GuillaumeFalourd/wait-sleep-action/actions/workflows/ubuntu_action_test.yml) [![Action test on MacOS](https://github.com/GuillaumeFalourd/wait-sleep-action/actions/workflows/macos_action_test.yml/badge.svg)](https://github.com/GuillaumeFalourd/wait-sleep-action/actions/workflows/macos_action_test.yml) [![Action test on Windows](https://github.com/GuillaumeFalourd/wait-sleep-action/actions/workflows/windows_action_test.yml/badge.svg)](https://github.com/GuillaumeFalourd/wait-sleep-action/actions/workflows/windows_action_test.yml)

☞ Github Action to wait / sleep during a job execution ⏱

_**Note**: This action is supported on **all runners** operating systems (`ubuntu`, `macos`, `windows`)_

## 📚 Usage

This action uses the Linux [sleep command](https://linux.die.net/man/1/sleep) to wait for a specific time during a job execution.

SUFFIX may be:
- `'s'` for seconds (default), 
- `'m'` for minutes, 
- `'h'` for hours,
- `'d'` for days.

_**Note**: The `sleep command` on MacOS only works with seconds, therefore this action converts the SUFFIX automatically to the value in seconds._

### Example

```yaml
    steps:
      - uses: GuillaumeFalourd/wait-sleep-action@v1
        with:
          time: '1m' # for 1 minute
```

## 🤝 Contributing

☞ If you're interested in contributing to this repository, please follow the [guidelines](https://github.com/GuillaumeFalourd/wait-sleep-action/blob/main/CONTRIBUTING.md)

## 🏅 Licensed

☞ This repository uses the [Apache License 2.0](https://github.com/GuillaumeFalourd/wait-sleep-action/blob/main/LICENSE)

<!-- ### Contribuidores

<a href="https://github.com/GuillaumeFalourd/wait-sleep-action/graphs/contributors">
  <img src="https://contrib.rocks/image?repo=GuillaumeFalourd/wait-sleep-action" />
</a>

(Criado com [contributors-img](https://contrib.rocks)) -->

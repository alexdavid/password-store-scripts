# Password-Store Scripts

A list of various scripts that compliment [pass](https://www.passwordstore.org/).

---

## `get-ages`
List all passwords from oldest to newest and print last change date

### Examples:
```shell
$ get-ages
personal/amazon     - 3 years ago
work/aws/my-product - 11 months ago
personal/github     - 1 month ago
personal/keybase    - 32 hours ago
work/stripe         - 11 minutes ago
```

## `get-older-than [age]`
Gets passwords that haven't been changed since the passed date/commit

### Examples:
To get passwords that were last modified over 3 months ago:
```shell
$ get-older-than 3 months ago
```
To get passwords modified over 1 year ago:
```shell
$ get-older-than 1 year ago
```

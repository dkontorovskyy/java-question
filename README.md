# java-question

## To reproduce:
- `mvn package`
- `dependency-check -s . -f HTML`
- `open dependency-check-report.html`


This is to be compared with the result of `Snyk test` or `snyk test --scan-all-unmanaged target --print-deps`

## Getting OWASP dependency-checker

`brew install dependency-check`
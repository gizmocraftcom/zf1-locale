# Changelog
## 2.0.0
Fork of `diablomedia/zendframework1-locale`, published as `gizmocraft/zendframework1-locale`.
### Breaking changes
- Requires PHP `>=8.5`. Tested on PHP 8.5 and 8.6.
- Package renamed from `diablomedia/zendframework1-locale` to `gizmocraft/zendframework1-locale`. It now requires `gizmocraft/zendframework1-exception`, `-registry`, `-xml` and `-cache`, all `^2.0.0`.
### Other changes
- No public signature changes and no library code changes were needed for PHP 8.5 and 8.6.
- Dev dependencies upgraded (PHPUnit 13, PHPStan 2.3, php-cs-fixer 3.95, GrumPHP 2.27). Dropped `composer-require-checker`, which has no release for PHP 8.6.
- Tests migrated to PHPUnit 13 attributes. CI runs PHP 8.5 and 8.6.

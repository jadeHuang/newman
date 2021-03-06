# Newman Changelog

#### Unreleased

- Fixed issue with environment and globals export format was using wrong property names (GH:553)
- Fixed issue where `--export-*` CLI option did not work with no parameters

#### v3.0.1 (Aug 9, 2016)

- Updated Postman Runtime to v2.4.1
- Newman now exits with a non-zero status code on test failures or errors

#### v3.0.0 (Aug 9, 2016)

- First stable release of Newman v3.0
- Added ability to suppress exit code on failures
- Renamed the "--stop-on-error" option to "--bail", which ensures that Newman stops on test failures or errors

#### v3.0.0-rc.1 (Aug 8, 2016)

- Initial release of Newman v3. [Migration Guide](MIGRATION.md)

> To view changelog for older versions, refer to https://github.com/postmanlabs/newman/blob/release/2.x/CHANGELOG.md

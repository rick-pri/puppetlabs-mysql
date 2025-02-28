# Change log

All notable changes to this project will be documented in this file. The format is based on [Keep a Changelog](http://keepachangelog.com/en/1.0.0/) and this project adheres to [Semantic Versioning](http://semver.org).

## [v10.0.0](https://github.com/puppetlabs/puppetlabs-mysql/tree/v10.0.0) (2019-06-26)

[Full Changelog](https://github.com/puppetlabs/puppetlabs-mysql/compare/v9.1.0...v10.0.0)

### Changed

- \(FM-7709\) pdksync and remove beaker [\#1210](https://github.com/puppetlabs/puppetlabs-mysql/pull/1210) ([tphoney](https://github.com/tphoney))

### Added

- add support for rh-mariadb102 [\#1209](https://github.com/puppetlabs/puppetlabs-mysql/pull/1209) ([martin-schlossarek](https://github.com/martin-schlossarek))
- Freebsd compat [\#1208](https://github.com/puppetlabs/puppetlabs-mysql/pull/1208) ([kapouik](https://github.com/kapouik))

### Fixed

- FM-7982 - update provisioner to docker\_exp [\#1205](https://github.com/puppetlabs/puppetlabs-mysql/pull/1205) ([lionce](https://github.com/lionce))

## [v9.1.0](https://github.com/puppetlabs/puppetlabs-mysql/tree/v9.1.0) (2019-06-10)

[Full Changelog](https://github.com/puppetlabs/puppetlabs-mysql/compare/v9.0.0...v9.1.0)

### Added

- Add option to specify $backupdir as a symlink target, for use with dm… [\#1200](https://github.com/puppetlabs/puppetlabs-mysql/pull/1200) ([comport3](https://github.com/comport3))
- \(FM-8029\) Add RedHat 8 support [\#1199](https://github.com/puppetlabs/puppetlabs-mysql/pull/1199) ([eimlav](https://github.com/eimlav))
- Allow own Xtrabackup script [\#1189](https://github.com/puppetlabs/puppetlabs-mysql/pull/1189) ([SaschaDoering](https://github.com/SaschaDoering))
- Litmus conversion [\#1175](https://github.com/puppetlabs/puppetlabs-mysql/pull/1175) ([pmcmaw](https://github.com/pmcmaw))

### Fixed

- \(MODULES-6875,MODULES-7487\) - Fix mariadb mysql\_user password idempotency [\#1195](https://github.com/puppetlabs/puppetlabs-mysql/pull/1195) ([alexjfisher](https://github.com/alexjfisher))

## [v9.0.0](https://github.com/puppetlabs/puppetlabs-mysql/tree/v9.0.0) (2019-05-21)

[Full Changelog](https://github.com/puppetlabs/puppetlabs-mysql/compare/8.1.0...v9.0.0)

### Changed

- pdksync - \(MODULES-8444\) - Raise lower Puppet bound [\#1184](https://github.com/puppetlabs/puppetlabs-mysql/pull/1184) ([david22swan](https://github.com/david22swan))

### Added

- Make incremental backups deactivable [\#1188](https://github.com/puppetlabs/puppetlabs-mysql/pull/1188) ([SaschaDoering](https://github.com/SaschaDoering))
- Allow multiple backupmethods [\#1187](https://github.com/puppetlabs/puppetlabs-mysql/pull/1187) ([SaschaDoering](https://github.com/SaschaDoering))

### Fixed

- Fix the contribution guide URL [\#1190](https://github.com/puppetlabs/puppetlabs-mysql/pull/1190) ([mauricemeyer](https://github.com/mauricemeyer))
- \(MODULES-8886\) Revert removal of deepmerge function [\#1181](https://github.com/puppetlabs/puppetlabs-mysql/pull/1181) ([eimlav](https://github.com/eimlav))
- Fixed Changelog links for 8.1.0 [\#1180](https://github.com/puppetlabs/puppetlabs-mysql/pull/1180) ([mauricemeyer](https://github.com/mauricemeyer))

## [8.1.0](https://github.com/puppetlabs/puppetlabs-mysql/tree/8.1.0) (2019-04-03)

[Full Changelog](https://github.com/puppetlabs/puppetlabs-mysql/compare/8.0.1...8.1.0)

### Added

- Rotate option for xtrabackup script [\#1176](https://github.com/puppetlabs/puppetlabs-mysql/pull/1176) ([elfranne](https://github.com/elfranne))
- Add support for dynamic backupmethods/mariabackup [\#1171](https://github.com/puppetlabs/puppetlabs-mysql/pull/1171) ([danquack](https://github.com/danquack))

### Fixed

- \(MODULES-6627\) Remove unused --host flags from mysqlcaller [\#1174](https://github.com/puppetlabs/puppetlabs-mysql/pull/1174) ([david22swan](https://github.com/david22swan))
- Set correct packagename for ruby\_mysql on Ubuntu 18.04 [\#1163](https://github.com/puppetlabs/puppetlabs-mysql/pull/1163) ([datty](https://github.com/datty))
- \[MODULES-8779\] Set proper python\_package\_name for RHEL/CentOS 8 [\#1161](https://github.com/puppetlabs/puppetlabs-mysql/pull/1161) ([javierpena](https://github.com/javierpena))
- fix install ordering for innodb data size [\#1160](https://github.com/puppetlabs/puppetlabs-mysql/pull/1160) ([fe80](https://github.com/fe80))

## [8.0.1](https://github.com/puppetlabs/puppetlabs-mysql/tree/8.0.1) (2019-03-20)

[Full Changelog](https://github.com/puppetlabs/puppetlabs-mysql/compare/8.0.0...8.0.1)

### Fixed

- \(MODULES-8684\) - Removing private tags from Puppet Types [\#1170](https://github.com/puppetlabs/puppetlabs-mysql/pull/1170) ([david22swan](https://github.com/david22swan))

## [8.0.0](https://github.com/puppetlabs/puppetlabs-mysql/tree/8.0.0) (2019-01-18)

[Full Changelog](https://github.com/puppetlabs/puppetlabs-mysql/compare/7.0.0...8.0.0)

### Changed

- \(MODULES-8193\) - Removal of inbuilt deepmerge and dirname functions [\#1145](https://github.com/puppetlabs/puppetlabs-mysql/pull/1145) ([david22swan](https://github.com/david22swan))

### Added

- \(MODULES-3539\) Allow @ in username [\#1155](https://github.com/puppetlabs/puppetlabs-mysql/pull/1155) ([Fogelholk](https://github.com/Fogelholk))
- \(MODULES-8144\) - Add support for SLES 15 [\#1146](https://github.com/puppetlabs/puppetlabs-mysql/pull/1146) ([eimlav](https://github.com/eimlav))
- Added support for RHSCL mysql versions and support for .mylogin.cnf for MySQL 5.6.6+ [\#1061](https://github.com/puppetlabs/puppetlabs-mysql/pull/1061) ([DJMuggs](https://github.com/DJMuggs))

### Fixed

- \(MODULES-8193\) - Wrapper methods created for inbuilt 4.x functions [\#1151](https://github.com/puppetlabs/puppetlabs-mysql/pull/1151) ([david22swan](https://github.com/david22swan))
- pdksync - \(FM-7655\) Fix rubygems-update for ruby \< 2.3 [\#1150](https://github.com/puppetlabs/puppetlabs-mysql/pull/1150) ([tphoney](https://github.com/tphoney))
- Add includedir for Gentoo [\#1147](https://github.com/puppetlabs/puppetlabs-mysql/pull/1147) ([baurmatt](https://github.com/baurmatt))
- add mysql\_native\_password for mariadb 10.2 in password\_hash [\#1117](https://github.com/puppetlabs/puppetlabs-mysql/pull/1117) ([mlk-89](https://github.com/mlk-89))
- Removing query\_cache ops that are no longer supported in MySQL \>= 8.0 [\#1107](https://github.com/puppetlabs/puppetlabs-mysql/pull/1107) ([ernstae](https://github.com/ernstae))

## [7.0.0](https://github.com/puppetlabs/puppetlabs-mysql/tree/7.0.0) (2018-10-25)

[Full Changelog](https://github.com/puppetlabs/puppetlabs-mysql/compare/6.2.0...7.0.0)

### Changed

- \(MODULES-6923\) remove staging module [\#1115](https://github.com/puppetlabs/puppetlabs-mysql/pull/1115) ([tphoney](https://github.com/tphoney))

### Added

- \(MODULES-7857\) Support user creation on galera [\#1130](https://github.com/puppetlabs/puppetlabs-mysql/pull/1130) ([MaxFedotov](https://github.com/MaxFedotov))
- MySQL 8 compatibility in user management [\#1092](https://github.com/puppetlabs/puppetlabs-mysql/pull/1092) ([zpetr](https://github.com/zpetr))

### Fixed

- \(MODULES-7487\) Check authentication string for user password on MariaDB 10.2.16+ [\#1135](https://github.com/puppetlabs/puppetlabs-mysql/pull/1135) ([gguillotte](https://github.com/gguillotte))

## [6.2.0](https://github.com/puppetlabs/puppetlabs-mysql/tree/6.2.0) (2018-09-27)

[Full Changelog](https://github.com/puppetlabs/puppetlabs-mysql/compare/6.1.0...6.2.0)

### Added

- pdksync - \(MODULES-6805\) metadata.json shows support for puppet 6 [\#1127](https://github.com/puppetlabs/puppetlabs-mysql/pull/1127) ([tphoney](https://github.com/tphoney))

### Fixed

- \(maint\) - Change versioning comparison [\#1123](https://github.com/puppetlabs/puppetlabs-mysql/pull/1123) ([eimlav](https://github.com/eimlav))

## [6.1.0](https://github.com/puppetlabs/puppetlabs-mysql/tree/6.1.0) (2018-09-13)

[Full Changelog](https://github.com/puppetlabs/puppetlabs-mysql/compare/6.0.0...6.1.0)

### Fixed

- pdksync - \(MODULES-7705\) - Bumping stdlib dependency from \< 5.0.0 to \< 6.0.0 [\#1114](https://github.com/puppetlabs/puppetlabs-mysql/pull/1114) ([pmcmaw](https://github.com/pmcmaw))
- \(MODULES-6981\) Do not try to read ~root/.my.cnf when calling "mysqld -V" [\#1063](https://github.com/puppetlabs/puppetlabs-mysql/pull/1063) ([simondeziel](https://github.com/simondeziel))

## [6.0.0](https://github.com/puppetlabs/puppetlabs-mysql/tree/6.0.0) (2018-08-01)

[Full Changelog](https://github.com/puppetlabs/puppetlabs-mysql/compare/5.4.0...6.0.0)

### Changed

- \[FM-6962\] Removal of unsupported OS from mysql [\#1086](https://github.com/puppetlabs/puppetlabs-mysql/pull/1086) ([david22swan](https://github.com/david22swan))

### Added

- \(FM-5985\) - Addition of support for Ubuntu 18.04 to mysql [\#1104](https://github.com/puppetlabs/puppetlabs-mysql/pull/1104) ([david22swan](https://github.com/david22swan))
- \(MODULES-7439\) - Implementing beaker-testmode\_switcher [\#1095](https://github.com/puppetlabs/puppetlabs-mysql/pull/1095) ([pmcmaw](https://github.com/pmcmaw))
- Support for optional\_\_args and prescript to mysqldump backup provider [\#1083](https://github.com/puppetlabs/puppetlabs-mysql/pull/1083) ([eputnam](https://github.com/eputnam))
- Allow empty user passwords [\#1075](https://github.com/puppetlabs/puppetlabs-mysql/pull/1075) ([disappear89](https://github.com/disappear89))
- Add user tls\_options and grant options to mysql::db [\#1065](https://github.com/puppetlabs/puppetlabs-mysql/pull/1065) ([edestecd](https://github.com/edestecd))
- Use puppet4 functions-api [\#1044](https://github.com/puppetlabs/puppetlabs-mysql/pull/1044) ([juliantodt](https://github.com/juliantodt))
- Replaced 'DROP USER' with 'DROP USER IF EXISTS' [\#942](https://github.com/puppetlabs/puppetlabs-mysql/pull/942) ([libertamohamed](https://github.com/libertamohamed))

### Fixed

- \(MODULES-7353\) Enable service for Debian 9  [\#1094](https://github.com/puppetlabs/puppetlabs-mysql/pull/1094) ([david22swan](https://github.com/david22swan))
- Update locales test for Debian 9 [\#1091](https://github.com/puppetlabs/puppetlabs-mysql/pull/1091) ([HelenCampbell](https://github.com/HelenCampbell))
- \[FM-7045\] Fix to allow Debian 9 test's to run clean [\#1088](https://github.com/puppetlabs/puppetlabs-mysql/pull/1088) ([david22swan](https://github.com/david22swan))
- \(MODULES-7198\) Fix DROP USER IF EXISTS on mariadb [\#1082](https://github.com/puppetlabs/puppetlabs-mysql/pull/1082) ([hunner](https://github.com/hunner))

## 5.4.0

### Added

- \(PDOC-210\) Puppet Strings documentation [\#1068](https://github.com/puppetlabs/puppetlabs-mysql/pull/1068) ([hunner](https://github.com/hunner))
- Compatibility for Alpine linux [\#1049](https://github.com/puppetlabs/puppetlabs-mysql/pull/1049) ([cisco87](https://github.com/cisco87))

### Fixed

- \(MODULES-6627\) Removed unused --host flag from mysqlcaller [\#1064](https://github.com/puppetlabs/puppetlabs-mysql/pull/1064) ([HelenCampbell](https://github.com/HelenCampbell))
- Fixed archlinux compatibility [\#1057](https://github.com/puppetlabs/puppetlabs-mysql/pull/1057) ([bastelfreak](https://github.com/bastelfreak))
- Changed input param option in export.json from sql to file [\#1054](https://github.com/puppetlabs/puppetlabs-mysql/pull/1054) ([cgoswami](https://github.com/cgoswami))

## Supported Release [5.3.0]
### Summary
This release uses the PDK convert functionality which in return makes the module PDK compliant. It also includes a roll up of maintenance changes, a new task and support for `GRANTS FUNCTION`.

### Added
- Add support for `GRANTS FUNCTION` ([MODULES-2075](https://tickets.puppet.com/browse/MODULES-2075)).
- Add Export database task.
- PDK Convert mysql ([MODULES-6454](https://tickets.puppet.com/browse/MODULES-6454)).

### Changed
- Allow authentication plugin to be changed.
- Update mysql_user provider.
- Plugins don't exist before 5.5; password field name changed
- Fix helpful rubocops and disable hurtful cops.
- Addressing puppet-lint and rubocop errors
- Remove update bundler and add ignore .DS_Store
- Skip rubocop warning in task.
- Fix a typo in a classname in the changelog.

## Supported Release [5.2.1]
### Summary
This release fixes CVE-2018-6508 which is a potential arbitrary code execution via tasks.

### Fixed
- Fix export and mysql tasks for arbitrary remote code

## Supported Release [5.2.0]

### Added
- Compatibility for puppet-staging 3.0.0

### Fixed
- Centralize all mysql command calls for providers
- Add paths to `mysql_datadir` provider for RedHat Software Collections

## Supported Release [5.1.0]
### Summary
This release adds Tasks to the Mysql module.

#### Added
- Adds the execute sql task.

## Supported Release [5.0.0]
### Summary
This is a major release that adds support for string translation. Currently the only supported language besides
English is Japanese.

#### Added
- Several gem dependencies required for translation.
- Wrapping of strings that require translation. Strings in ruby code are now wrapped with `_()` and strings in puppet code with `translate()`.
- Debian 9 support

#### Changed
- The default php_package_name for Debian and Ubuntu to `php-mysql`

## Supported Release 4.0.1
### Summary
This is a small bugfix release that makes `mysql_install_db` optional and fixes some regular expression issues.

#### Bugfixes
- ([MODULES-5528](https://tickets.puppet.com/browse/MODULES-5528)) Fixes the `mysql_install_db` command so that it is optional
- ([MODULES-5602](https://tickets.puppet.com/browse/MODULES-5602)) Removes superfluous backslashes in some regular expressions that were causing instability

## Supported Release 4.0.0
### Summary
This release sees the enablement of rubocop, also an update to the lib directory with rubocop fixes and several other changes and fixes. Also a bump to the Puppet version compatibility and several Puppet language updates.

#### Added
- Updated README.md with example how to install MySQL Community Server 5.6 on Centos 7.3
- Enabled Rubocop and addition of Rubocop fixes for /lib directory.

#### Removed
- Dropped legacy tests for db.pp.

#### Changed
- Replaced validate function calls with datatypes in db.pp.
- Bumped recommended puppet version to between 4.7.0 and 6.0.0.
- Conditionalize name validation in mysql_grant type. ([MODULES-4604](https://tickets.puppet.com/browse/MODULES-4604))

#### Fixed
- Removal of invalid parameter provider on Mysql_user[user@localhost] in mysql::db ([MODULES-4115](https://tickets.puppet.com/browse/MODULES-4115))
- Fixed server_service_name for Debian/stretch.
- Spec fixes for Puppet 5.
- Test update for fix:create procedure, then grant ([MODULES-5390](https://tickets.puppet.com/browse/MODULES-5390))
- Fixing empty user/password issue for xtrabackup. Now defaults as undef instead of ''.
- Remove unsupported Ubuntu versions ([MODULES-5501](https://tickets.puppet.com/browse/MODULES-5501))

## Supported Release 3.11.0
### Summary
This release includes README and metadata translations to Japanese, as well as some enhancements and bugfixes.

#### Added
- New flag for successful backups
- Solaris support improvements
- New parameter `optional_args` for extra innobackupex options
- Specify environment variables (e.g. https_proxy) for MySQLTuner download.
- Check to only install bzip2 if `$backupcompress` is `true`
- Debian 9 compatibility
- Japanese README

#### Fixed
- Syntax errors
- Bug where error logs were being created before the datadir was initialized (MODULES-4743)

## Supported Release 3.10.0
### Summary
This release includes new features for setting TLS options on a mysql user, a new parameter to allow specifying tool to import sql files, as well as various bugfixes.

#### Features
- (MODULES-3879) Adds `import_cat_cmd` parameter to specify the command to read sql files
- Adds support for setting `tls_options` in `mysql_user`

#### Bugfixes
- (MODULES-3557) Adds Ubuntu 16.04 package names for language bindings
- (MODULES-3907) Adds MySQL/Percona 5.7 initialize on fresh deploy

## Supported Release 3.9.0
### Summary
This release adds Percona 5.7 support and compatibility with Ubuntu 16.04, in addition to various bugfixes.

#### Features
- (MODULES-3441) Adds the `mysqld_version` fact
- (MODULES-3513) Adds a new backup dump parameter `maxallowedpacket`
- Adds new parameter `xtrabackup_package_name` to `mysql::backup::xtrabackup` class
- Adds ability to revoke GRANT privilege

#### Bugfixes
- Fixes a bug where `mysql_user` fails if facter cannot retrieve fqdn.
- Fix global parameter usage in backup script
- Adds support for `puppet-staging` version `2.0.0`
- (MODULES-3601) Moves binary logging configuration to take place after package install
- (MODULES-3711) Add limit to mysql server ID generated value
- (MODULES-3698) Fixes defaults for SLES12
- Updates user name length restrictions for MySQL version 5.7.8 and above.
- Fixes a bug where error log is not writable by owner

## Supported Release 3.8.0
### Summary
This release adds Percona 5.7 support and compatibility with Ubuntu 16.04, in addition to various bugfixes.

#### Features
- Adds support for Percona 5.7
- Adds support for Ubuntu 16.04 (Xenial)

#### Known Limitations
- The mysqlbackup.sh script will not work on MySQL 5.7.0 and up.

#### Bugfixes
- Use mysql_install_db only with uniq defaults-extra-file
- Updates mysqlbackup.sh to ensure backup directory exist
- Loosen MariaDB recognition to fix it on Debian 8
- Allow mysql::backup::mysqldump to access root_group in tests
- Fixed problem with ignoring parameters from global configs
- Fixes ordering issue that initialized mysqld before config is set
- (MODULES-1256) Fix parameters on OpenSUSE 12
- Fixes install errors on Debian-based OS by configuring the base of includedir
- Configure the configfile location for mariadb
- Default mysqld_type return value should be 'mysql' if another type is not detected
- Make sure that bzip2 is installed before setting up the cron tab job using mysqlbackup.sh
- Fixes path issue on FreeBSD
- Check that /var/lib/mysql actually contains files
- Removes mysql regex when checking type
- (MODULES-2111) Add the system database to user related actions
- Updates default group for logfiles on Debian-based OS to 'adm'
- Fixes an issue with Amazon linux major release 4 installation
- Fixes 'mysql_install_db' script support on Gentoo
- Removes erroneous anchors to mysql::client from mysql::db
- Adds path to be able to find MySQL 5.5 installation on CentOS

## Supported Release 3.7.0
### Summary

A large release with several new features. Also includes a considerable amount of bugfixes, many around compatibility and improvements to current functionality.

#### Features

- Now uses mariadb in OpenSuSE >= 13.1.
- Switch to rspec-puppet-facts.
- Additional function to check if table exists before grant.
- Add ability to input password hash directly.
- Now checking major release instead of specific release.
- Debian 8 support.

#### Bugfixes

- Minor doc update.
- Fixes improper use of function `warn` in backup manifest of server.
- Fixes to Compatibility with PE 3.3.
- Fixes `when not managing config file` in `mysql_server_spec`.
- Improved user validation and munging.
- Fixes fetching the mysql_user password for MySQL >=5.7.6.
- Fixes unique server_id within my.cnf, the issue were the entire mac address was not being read in to generate the id.
- Corrects the daemon_dev_package_name for mariadb on redhat.
- Fix version compare to properly suppress show_diff for root password.
- Fixes to ensure compatibility with future parser.
- Solaris removed from PE in metadata as its not supported.
- Use MYSQL_PWD to avoid mysqldump warnings.
- Use temp cnf file instead of env variable which creates acceptance test failures.
- No longer hash passwords that are already hashed.
- Fix Gemfile to work with ruby 1.8.7.
- Fixed MySQL 5.7.6++ compatibility.
- Fixing error when disabling service management and the service does not exist.
- Ubuntu vivid should use systemd not upstart.
- Fixed new mysql_datadir provider on CentOS for MySQl 5.7.6 compatibility.
- Ensure if service restart to wait till mysql is up.
- Move all dependencies to not have them in case of service unmanaged.
- Re-Added the ability to set a empty string as option parameter.
- Fixes edge-case with dropping pre-existing users with grants.
- Fix logic for choosing rspec version.
- Refactored main acceptance suite.
- Skip idempotency tests on test cells that do have PUP-5016 unfixed.
- Fix tmpdir to be shared across examples.
- Update to current msync configs [006831f].
- Fix mysql_grant with MySQL ANSI_QUOTES mode.
- Generate .my.cnf for all sections.

## Supported Release 3.6.2
### Summary

Small release for support of newer PE versions. This increments the version of PE in the metadata.json file.

## 2015-09-22 - Supported Release 3.6.1
### Summary
This is a security and bugfix release that fixes incorrect username truncation in the munge for the mysql_user type, incorrect function used in `mysql::server::backup` and fixes compatibility issues with PE 3.3.x.

#### Bugfixes
- Loosen the regex in mysql_user munging so the username is not unintentionally truncated.
- Use `warning()` not `warn()`
- Metadata had inadvertantly dropped 3.3.x support
- Some 3.3.x compatibility issues in `mysqltuner` were corrected

## 2015-08-10 - Supported Release 3.6.0
### Summary
This release adds the ability to use mysql::db and `mysql_*` types against unmanaged or external mysql instances.

#### Features
- Add ability to use mysql::db WITHOUT mysql::server (ie, externally)
- Add prescript attribute to mysql::server::backup for xtrabackup
- Add postscript ability to xtrabackup provider.

#### Bugfixes
- Fix default root passwords blocking puppet on mysql 5.8
- Fix service dependency when package_manage is false
- Fix selinux permissions on my.cnf

## 2015-07-23 - Supported Release 3.5.0
### Summary
A small release to add explicit support to newer Puppet versions and accumulated patches.

#### Features/Improvements
- Start running tests against puppet 4
- Support longer usernames on newer MariaDB versions
- Add parameters for Solaris 11 and 12

#### Bugfixes
- Fix references to the mysql-server package
- mysql_server_id doesn't throw and error on machines without macaddress

## 2015-05-19 - Supported Release 3.4.0
### Summary
This release includes the addition of extra facts, OpenBSD compatibility, and a number of other features, improvements and bug fixes.

#### Features/Improvements
- Added server_id fact which includes mac address for better uniqueness
- Added OpenBSD compatibility, only for 'OpenBSD -current' (due to the recent switch to mariadb)
- Added a $mysql_group parameter, and use that instead of the $root_group parameter to define the group membership of the mysql error log file.
- Updated tests for rspec-puppet 2 and future parser
- Further acceptance testing improvements
- MODULES-1928 - allow log-error to be undef
- Split package installation and database install
- README wording improvements
- Added options for including/excluding triggers and routines
- Made the 'TRIGGER' privilege of mysqldump backups depend on whether or not we are actually backing up triggers
- Cleaned up the privilege assignment in the mysqldump backup script
- Add a fact for capturing the mysql version installed

#### Bugfixes
- mysql backup: fix regression in mysql_user call
- Set service_ensure to undef, in the case of an unmanaged service
- README Typos fixed
- Bugfix on Xtrabackup crons
- Fixed a permission problem that was preventing triggers from being backed up
- MODULES-1981: Revoke and grant difference of old and new privileges
- Fix an issue were we assume triggers work
- Change default for mysql::server::backup to ignore_triggers = false

#### Deprecations
mysql::server::old_root_password property

## 2015-03-03 - Supported Release 3.3.0
### Summary
This release includes major README updates, the addition of backup providers, and a fix for managing the log-bin directory.

#### Features
- Add package_manage parameters to `mysql::server` and `mysql::client` (MODULES-1143)
- README improvements
- Add `mysqldump`, `mysqlbackup`, and `xtrabackup` backup providers.

#### Bugfixes
- log-error overrides were not being properly used (MODULES-1804)
- check for full path for log-bin to stop puppet from managing file '.'

## 2015-02-09 - Supported Release 3.2.0
### Summary
This release includes several new features and bugfixes, including support for various plugins, making the output from mysql_password more consistent when input is empty and improved username validation.

#### Features
- Add type and provider to manage plugins
- Add support for authentication plugins
- Add support for mysql_install_db on freebsd
- Add `create_root_user` and `create_root_my_cnf` parameters to `mysql::server`

#### Bugfixes
- Remove dependency on stdlib >= 4.1.0 (MODULES-1759)
- Make grant autorequire user
- Remove invalid parameter 'provider' from mysql_user instance (MODULES-1731)
- Return empty string for empty input in mysql_password
- Fix `mysql::account_security` when fqdn==localhost
- Update username validation (MODULES-1520)
- Future parser fix in params.pp
- Fix package name for debian 8
- Don't start the service until the server package is installed and the config file is in place
- Test fixes
- Lint fixes

## 2014-12-16 - Supported Release 3.1.0
### Summary

This release includes several new features, including SLES12 support, and a number of bug fixes.

#### Notes

`mysql::server::mysqltuner` has been refactored to fetch the mysqltuner script from github by default. If you are running on a non-network-connected system, you will need to download that file and have it available to your node at a path specified by the `source` parameter to the `mysqltuner` class.

#### Features
- Add support for install_options for all package resources (MODULES-1484)
- Add log-bin directory creation
- Allow mysql::db to import multiple files (MODULES-1338)
- SLES12 support
- Improved identifier quoting detections
- Reworked `mysql::server::mysqltuner` so that we are no longer packaging the script as it is licensed under the GPL.

#### Bugfixes
- Fix regression in username validation
- Proper containment for mysql::client in mysql::db
- Support quoted usernames of length 15 and 16 chars

## 2014-11-11 - Supported Release 3.0.0
### Summary

Added several new features including MariaDB support and future parser

#### Backwards-incompatible Changes
* Remove the deprecated `database`, `database_user`, and `database_grant` resources. The correct resources to use are `mysql`, `mysql_user`, and `mysql_grant` respectively.

#### Features
* Add MariaDB Support
* The mysqltuner perl script has been updated to 1.3.0 based on work at http://github.com/major/MySQLTuner-perl
* Add future parse support, fixed issues with undef to empty string
* Pass the backup credentials to 'SHOW DATABASES'
* Ability to specify the Includedir for `mysql::server`
* `mysql::db` now has an import\_timeout feature that defaults to 300
* The `mysql` class has been removed
* `mysql::server` now takes an `override_options` hash that will affect the installation
* Ability to install both dev and client dev

#### BugFix
* `mysql::server::backup` now passes `ensure` param to the nested `mysql_grant`
* `mysql::server::service` now properly requires the presence of the `log_error` file
* `mysql::config` now occurs before `mysql::server::install_db` correctly

## 2014-07-15 - Supported Release 2.3.1
### Summary

This release merely updates metadata.json so the module can be uninstalled and
upgraded via the puppet module command.

## 2014-05-14 - Supported Release 2.3.0

This release primarily adds support for RHEL7 and Ubuntu 14.04 but it
also adds a couple of new parameters to allow for further customization,
as well as ensuring backups can backup stored procedures properly.

#### Features
Added `execpath` to allow a custom executable path for non-standard mysql installations.
Added `dbname` to mysql::db and use ensure_resource to create the resource.
Added support for RHEL7 and Fedora Rawhide.
Added support for Ubuntu 14.04.
Create a warning for if you disable SSL.
Ensure the error logfile is owned by MySQL.
Disable ssl on FreeBSD.
Add PROCESS privilege for backups.

#### Bugfixes

#### Known Bugs
* No known bugs

## 2014-03-04 - Supported Release 2.2.3
### Summary

This is a supported release.  This release removes a testing symlink that can
cause trouble on systems where /var is on a seperate filesystem from the
modulepath.

#### Features
#### Bugfixes
#### Known Bugs
* No known bugs

## 2014-03-04 - Supported Release 2.2.2
### Summary
This is a supported release. Mostly comprised of enhanced testing, plus a
bugfix for Suse.

#### Bugfixes
- PHP bindings on Suse
- Test fixes

#### Known Bugs
* No known bugs

## 2014-02-19 - Version 2.2.1

### Summary

Minor release that repairs mysql_database{} so that it sees the correct
collation settings (it was only checking the global mysql ones, not the
actual database and constantly setting it over and over since January 22nd).

Also fixes a bunch of tests on various platforms.


## 2014-02-13 - Version 2.2.0

### Summary

#### Features
- Add `backupdirmode`, `backupdirowner`, `backupdirgroup` to
  mysql::server::backup to allow customizing the mysqlbackupdir.
- Support multiple options of the same name, allowing you to
  do 'replicate-do-db' => ['base1', 'base2', 'base3'] in order to get three
  lines of replicate-do-db = base1, replicate-do-db = base2 etc.

#### Bugfixes
- Fix `restart` so it actually stops mysql restarting if set to false.
- DRY out the defaults_file functionality in the providers.
- mysql_grant fixed to work with root@localhost/@.
- mysql_grant fixed for WITH MAX_QUERIES_PER_HOUR
- mysql_grant fixed so revoking all privileges accounts for GRANT OPTION
- mysql_grant fixed to remove duplicate privileges.
- mysql_grant fixed to handle PROCEDURES when removing privileges.
- mysql_database won't try to create existing databases, breaking replication.
- bind_address renamed bind-address in 'mysqld' options.
- key_buffer renamed to key_buffer_size.
- log_error renamed to log-error.
- pid_file renamed to pid-file.
- Ensure mysql::server::root_password runs before mysql::server::backup
- Fix options_override -> override_options in the README.
- Extensively rewrite the README to be accurate and awesome.
- Move to requiring stdlib 3.2.0, shipped in PE3.0
- Add many new tests.


## 2013-11-13 - Version 2.1.0

### Summary

The most important changes in 2.1.0 are improvements to the my.cnf creation,
as well as providers.  Setting options to = true strips them to be just the
key name itself, which is required for some options.

The provider updates fix a number of bugs, from lowercase privileges to
deprecation warnings.

Last, the new hiera integration functionality should make it easier to
externalize all your grants, users, and, databases.  Another great set of
community submissions helped to make this release.

#### Features
- Some options can not take a argument. Gets rid of the '= true' when an
option is set to true.
- Easier hiera integration:  Add hash parameters to mysql::server to allow
specifying grants, users, and databases.

#### Bugfixes
- Fix an issue with lowercase privileges in mysql_grant{} causing them to be reapplied needlessly.
- Changed defaults-file to defaults-extra-file in providers.
- Ensure /root/.my.cnf is 0600 and root owned.
- database_user deprecation warning was incorrect.
- Add anchor pattern for client.pp
- Documentation improvements.
- Various test fixes.


## 2013-10-21 - Version 2.0.1

### Summary

This is a bugfix release to handle an issue where unsorted mysql_grant{}
privileges could cause Puppet to incorrectly reapply the permissions on
each run.

#### Bugfixes
- Mysql_grant now sorts privileges in the type and provider for comparison.
- Comment and test tweak for PE3.1.


## 2013-10-14 - Version 2.0.0

### Summary

(Previously detailed in the changelog for 2.0.0-rc1)

This module has been completely refactored and works significantly different.
The changes are broad and touch almost every piece of the module.

See the README.md for full details of all changes and syntax.
Please remain on 1.0.0 if you don't have time to fully test this in dev.

* mysql::server, mysql::client, and mysql::bindings are the primary interface
classes.
* mysql::server takes an `override_options` parameter to set my.cnf options,
with the hash format: { 'section' => { 'thing' => 'value' }}
* mysql attempts backwards compatibility by forwarding all parameters to
mysql::server.


## 2013-10-09 - Version 2.0.0-rc5

### Summary

Hopefully the final rc!  Further fixes to mysql_grant (stripping out the
cleverness so we match a much wider range of input.)

#### Bugfixes
- Make mysql_grant accept '.*'@'.*' in terms of input for user@host.


## 2013-10-09 - Version 2.0.0-rc4

### Summary

Bugfixes to mysql_grant and mysql_user form the bulk of this rc, as well as
ensuring that values in the override_options hash that contain a value of ''
are created as just "key" in the conf rather than "key =" or "key = false".

#### Bugfixes
- Improve mysql_grant to work with IPv6 addresses (both long and short).
- Ensure @host users work as well as user@host users.
- Updated my.cnf template to support items with no values.


## 2013-10-07 - Version 2.0.0-rc3

### Summary
Fix mysql::server::monitor's use of mysql_user{}.

#### Bugfixes
- Fix myql::server::monitor's use of mysql_user{} to grant the proper
permissions.  Add specs as well.  (Thanks to treydock!)


## 2013-10-03 - Version 2.0.0-rc2

### Summary
Bugfixes

#### Bugfixes
- Fix a duplicate parameter in mysql::server


## 2013-10-03 - Version 2.0.0-rc1

### Summary

This module has been completely refactored and works significantly different.
The changes are broad and touch almost every piece of the module.

See the README.md for full details of all changes and syntax.
Please remain on 1.0.0 if you don't have time to fully test this in dev.

* mysql::server, mysql::client, and mysql::bindings are the primary interface
classes.
* mysql::server takes an `override_options` parameter to set my.cnf options,
with the hash format: { 'section' => { 'thing' => 'value' }}
* mysql attempts backwards compatibility by forwarding all parameters to
mysql::server.

---
## 2013-09-23 - Version 1.0.0

### Summary

This release introduces a number of new type/providers, to eventually
replace the database_ ones.  The module has been converted to call the
new providers rather than the previous ones as they have a number of
fixes, additional options, and work with puppet resource.

This 1.0.0 release precedes a large refactoring that will be released
almost immediately after as 2.0.0.

#### Features
- Added mysql_grant, mysql_database, and mysql_user.
- Add `mysql::bindings` class and refactor all other bindings to be contained underneath mysql::bindings:: namespace.
- Added support to back up specified databases only with 'mysqlbackup' parameter.
- Add option to mysql::backup to set the backup script to perform a mysqldump on each database to its own file

#### Bugfixes
- Update my.cnf.pass.erb to allow custom socket support
- Add environment variable for .my.cnf in mysql::db.
- Add HOME environment variable for .my.cnf to mysqladmin command when
(re)setting root password

---
## 2013-07-15 - Version 0.9.0
#### Features
- Add `mysql::backup::backuprotate` parameter
- Add `mysql::backup::delete_before_dump` parameter
- Add `max_user_connections` attribute to `database_user` type

#### Bugfixes
- Add client package dependency for `mysql::db`
- Remove duplicate `expire_logs_days` and `max_binlog_size` settings
- Make root's `.my.cnf` file path dynamic
- Update pidfile path for Suse variants
- Fixes for lint

## 2013-07-05 - Version 0.8.1
#### Bugfixes
 - Fix a typo in the Fedora 19 support.

## 2013-07-01 - Version 0.8.0
#### Features
 - mysql::perl class to install perl-DBD-mysql.
 - minor improvements to the providers to improve reliability
 - Install the MariaDB packages on Fedora 19 instead of MySQL.
 - Add new `mysql` class parameters:
   -  `max_connections`: The maximum number of allowed connections.
   -  `manage_config_file`: Opt out of puppetized control of my.cnf.
   -  `ft_min_word_len`: Fine tune the full text search.
   -  `ft_max_word_len`: Fine tune the full text search.
 - Add new `mysql` class performance tuning parameters:
   -  `key_buffer`
   -  `thread_stack`
   -  `thread_cache_size`
   -  `myisam-recover`
   -  `query_cache_limit`
   -  `query_cache_size`
   -  `max_connections`
   -  `tmp_table_size`
   -  `table_open_cache`
   -  `long_query_time`
 - Add new `mysql` class replication parameters:
   -  `server_id`
   -  `sql_log_bin`
   -  `log_bin`
   -  `max_binlog_size`
   -  `binlog_do_db`
   -  `expire_logs_days`
   -  `log_bin_trust_function_creators`
   -  `replicate_ignore_table`
   -  `replicate_wild_do_table`
   -  `replicate_wild_ignore_table`
   -  `expire_logs_days`
   -  `max_binlog_size`

#### Bugfixes
 - No longer restart MySQL when /root/.my.cnf changes.
 - Ensure mysql::config runs before any mysql::db defines.

## 2013-06-26 - Version 0.7.1
#### Bugfixes
- Single-quote password for special characters
- Update travis testing for puppet 3.2.x and missing Bundler gems

## 2013-06-25 - Version 0.7.0
This is a maintenance release for community bugfixes and exposing
configuration variables.

* Add new `mysql` class parameters:
  -  `basedir`: The base directory mysql uses
  -  `bind_address`: The IP mysql binds to
  -  `client_package_name`: The name of the mysql client package
  -  `config_file`: The location of the server config file
  -  `config_template`: The template to use to generate my.cnf
  -  `datadir`: The directory MySQL's datafiles are stored
  -  `default_engine`: The default engine to use for tables
  -  `etc_root_password`: Whether or not to add the mysql root password to
 /etc/my.cnf
  -  `java_package_name`: The name of the java package containing the java
 connector
  -  `log_error`: Where to log errors
  -  `manage_service`: Boolean dictating if mysql::server should manage the
 service
  -  `max_allowed_packet`: Maximum network packet size mysqld will accept
  -  `old_root_password`: Previous root user password
  -  `php_package_name`: The name of the phpmysql package to install
  -  `pidfile`: The location mysql will expect the pidfile to be
  -  `port`: The port mysql listens on
  -  `purge_conf_dir`: Value fed to recurse and purge parameters of the
 /etc/mysql/conf.d resource
  -  `python_package_name`: The name of the python mysql package to install
  -  `restart`: Whether to restart mysqld
  -  `root_group`: Use specified group for root-owned files
  -  `root_password`: The root MySQL password to use
  -  `ruby_package_name`: The name of the ruby mysql package to install
  -  `ruby_package_provider`: The installation suite to use when installing the
 ruby package
  -  `server_package_name`: The name of the server package to install
  -  `service_name`: The name of the service to start
  -  `service_provider`: The name of the service provider
  -  `socket`: The location of the MySQL server socket file
  -  `ssl_ca`: The location of the SSL CA Cert
  -  `ssl_cert`: The location of the SSL Certificate to use
  -  `ssl_key`: The SSL key to use
  -  `ssl`: Whether or not to enable ssl
  -  `tmpdir`: The directory MySQL's tmpfiles are stored
* Deprecate `mysql::package_name` parameter in favor of
`mysql::client_package_name`
* Fix local variable template deprecation
* Fix dependency ordering in `mysql::db`
* Fix ANSI quoting in queries
* Fix travis support (but still messy)
* Fix typos

## 2013-01-11 - Version 0.6.1
* Fix providers when /root/.my.cnf is absent

## 2013-01-09 - Version 0.6.0
* Add `mysql::server::config` define for specific config directives
* Add `mysql::php` class for php support
* Add `backupcompress` parameter to `mysql::backup`
* Add `restart` parameter to `mysql::config`
* Add `purge_conf_dir` parameter to `mysql::config`
* Add `manage_service` parameter to `mysql::server`
* Add syslog logging support via the `log_error` parameter
* Add initial SuSE support
* Fix remove non-localhost root user when fqdn != hostname
* Fix dependency in `mysql::server::monitor`
* Fix .my.cnf path for root user and root password
* Fix ipv6 support for users
* Fix / update various spec tests
* Fix typos
* Fix lint warnings

## 2012-08-23 - Version 0.5.0
* Add puppetlabs/stdlib as requirement
* Add validation for mysql privs in provider
* Add `pidfile` parameter to mysql::config
* Add `ensure` parameter to mysql::db
* Add Amazon linux support
* Change `bind_address` parameter to be optional in my.cnf template
* Fix quoting root passwords

## 2012-07-24 - Version 0.4.0
* Fix various bugs regarding database names
* FreeBSD support
* Allow specifying the storage engine
* Add a backup class
* Add a security class to purge default accounts

## 2012-05-03 - Version 0.3.0
* 14218 Query the database for available privileges
* Add mysql::java class for java connector installation
* Use correct error log location on different distros
* Fix set_mysql_rootpw to properly depend on my.cnf

## 2012-04-11 - Version 0.2.0

## 2012-03-19 - William Van Hevelingen <blkperl@cat.pdx.edu>
* (#13203) Add ssl support (f7e0ea5)

## 2012-03-18 - Nan Liu <nan@puppetlabs.com>
* Travis ci before script needs success exit code. (0ea463b)

## 2012-03-18 - Nan Liu <nan@puppetlabs.com>
* Fix Puppet 2.6 compilation issues. (9ebbbc4)

## 2012-03-16 - Nan Liu <nan@puppetlabs.com>
* Add travis.ci for testing multiple puppet versions. (33c72ef)

## 2012-03-15 - William Van Hevelingen <blkperl@cat.pdx.edu>
* (#13163) Datadir should be configurable (f353fc6)

## 2012-03-16 - Nan Liu <nan@puppetlabs.com>
* Document create_resources dependency. (558a59c)

## 2012-03-16 - Nan Liu <nan@puppetlabs.com>
* Fix spec test issues related to error message. (eff79b5)

## 2012-03-16 - Nan Liu <nan@puppetlabs.com>
* Fix mysql service on Ubuntu. (72da2c5)

## 2012-03-16 - Dan Bode <dan@puppetlabs.com>
* Add more spec test coverage (55e399d)

## 2012-03-16 - Nan Liu <nan@puppetlabs.com>
* (#11963) Fix spec test due to path changes. (1700349)

## 2012-03-07 - François Charlier <fcharlier@ploup.net>
* Add a test to check path for 'mysqld-restart' (b14c7d1)

## 2012-03-07 - François Charlier <fcharlier@ploup.net>
* Fix path for 'mysqld-restart' (1a9ae6b)

## 2012-03-15 - Dan Bode <dan@puppetlabs.com>
* Add rspec-puppet tests for mysql::config (907331a)

## 2012-03-15 - Dan Bode <dan@puppetlabs.com>
* Moved class dependency between sever and config to server (da62ad6)

## 2012-03-14 - Dan Bode <dan@puppetlabs.com>
* Notify mysql restart from set_mysql_rootpw exec (0832a2c)

## 2012-03-15 - Nan Liu <nan@puppetlabs.com>
* Add documentation related to osfamily fact. (8265d28)

## 2012-03-14 - Dan Bode <dan@puppetlabs.com>
* Mention osfamily value in failure message (e472d3b)

## 2012-03-14 - Dan Bode <dan@puppetlabs.com>
* Fix bug when querying for all database users (015490c)

## 2012-02-09 - Nan Liu <nan@puppetlabs.com>
* Major refactor of mysql module. (b1f90fd)

## 2012-01-11 - Justin Ellison <justin.ellison@buckle.com>
* Ruby and Python's MySQL libraries are named differently on different distros. (1e926b4)

## 2012-01-11 - Justin Ellison <justin.ellison@buckle.com>
* Per @ghoneycutt, we should fail explicitly and explain why. (09af083)

## 2012-01-11 - Justin Ellison <justin.ellison@buckle.com>
* Removing duplicate declaration (7513d03)

## 2012-01-10 - Justin Ellison <justin.ellison@buckle.com>
* Use socket value from params class instead of hardcoding. (663e97c)

## 2012-01-10 - Justin Ellison <justin.ellison@buckle.com>
* Instead of hardcoding the config file target, pull it from mysql::params (031a47d)

## 2012-01-10 - Justin Ellison <justin.ellison@buckle.com>
* Moved $socket to within the case to toggle between distros.  Added a $config_file variable to allow per-distro config file destinations. (360eacd)

## 2012-01-10 - Justin Ellison <justin.ellison@buckle.com>
* Pretty sure this is a bug, 99% of Linux distros out there won't ever hit the default. (3462e6b)

## 2012-02-09 - William Van Hevelingen <blkperl@cat.pdx.edu>
* Changed the README to use markdown (3b7dfeb)

## 2012-02-04 - Daniel Black <grooverdan@users.sourceforge.net>
* (#12412) mysqltuner.pl update (b809e6f)

## 2011-11-17 - Matthias Pigulla <mp@webfactory.de>
* (#11363) Add two missing privileges to grant: event_priv, trigger_priv (d15c9d1)

## 2011-12-20 - Jeff McCune <jeff@puppetlabs.com>
* (minor) Fixup typos in Modulefile metadata (a0ed6a1)

## 2011-12-19 - Carl Caum <carl@carlcaum.com>
* Only notify Exec to import sql if sql is given (0783c74)

## 2011-12-19 - Carl Caum <carl@carlcaum.com>
* (#11508) Only load sql_scripts on DB creation (e3b9fd9)

## 2011-12-13 - Justin Ellison <justin.ellison@buckle.com>
* Require not needed due to implicit dependencies (3058feb)

## 2011-12-13 - Justin Ellison <justin.ellison@buckle.com>
* Bug #11375: puppetlabs-mysql fails on CentOS/RHEL (a557b8d)

## 2011-06-03 - Dan Bode <dan@puppetlabs.com> - 0.0.1
* initial commit

[5.4.0]:https://github.com/puppetlabs/puppetlabs-mysql/compare/5.3.0...5.4.0
[5.3.0]:https://github.com/puppetlabs/puppetlabs-mysql/compare/5.2.1...5.3.0
[5.2.1]:https://github.com/puppetlabs/puppetlabs-mysql/compare/5.2.0...5.2.1
[5.2.0]:https://github.com/puppetlabs/puppetlabs-mysql/compare/5.1.0...5.2.0
[5.1.0]:https://github.com/puppetlabs/puppetlabs-mysql/compare/5.0.0...5.1.0
[5.0.0]:https://github.com/puppetlabs/puppetlabs-mysql/compare/4.0.1...5.0.0


\* *This Changelog was automatically generated by [github_changelog_generator](https://github.com/skywinder/Github-Changelog-Generator)*

[![Runbot Status](https://runbot.odoo-community.org/runbot/badge/flat/149/10.0.svg)](https://runbot.odoo-community.org/runbot/repo/github-com-oca-server-tools-149)
[![Build Status](https://travis-ci.org/OCA/server-tools.svg?branch=10.0)](https://travis-ci.org/OCA/server-tools)
[![Coverage Status](https://coveralls.io/repos/OCA/server-tools/badge.png?branch=10.0)](https://coveralls.io/r/OCA/server-tools?branch=10.0)
[![Code Climate](https://codeclimate.com/github/OCA/server-tools/badges/gpa.svg)](https://codeclimate.com/github/OCA/server-tools)

Server Environment And Tools
============================

This project aim to deal with modules related to manage Odoo server environment and provide useful tools. You'll find modules that:

 - Manage configuration depending on environment (devs, test, prod,..)
 - Keep the security on update
 - Manage email settings

[//]: # (addons)

Available addons
----------------
addon | version | maintainers | summary
--- | --- | --- | ---
[attachment_base_synchronize](attachment_base_synchronize/) | 10.0.1.0.0 |  | Attachment Base Synchronize
[auditlog](auditlog/) | 10.0.1.0.1 |  | Audit Log
[auth_admin_passkey](auth_admin_passkey/) | 10.0.1.0.3 |  | Authentification - Admin Passkey
[auth_brute_force](auth_brute_force/) | 10.0.2.2.0 |  | Track Authentication Attempts and Prevent Brute-force Attacks
[auth_oauth_multi_token](auth_oauth_multi_token/) | 10.0.1.0.0 |  | Allow multiple connection with the same OAuth account
[auth_session_timeout](auth_session_timeout/) | 10.0.1.0.3 |  | This module disable all inactive sessions since a given delay
[auth_signup_verify_email](auth_signup_verify_email/) | 10.0.2.0.0 |  | Force uninvited users to use a good email for signup
[auth_supplier](auth_supplier/) | 10.0.1.0.0 |  | Auth Supplier
[auth_totp](auth_totp/) | 10.0.2.0.1 |  | Allows users to enable MFA and add optional trusted devices
[auth_totp_password_security](auth_totp_password_security/) | 10.0.1.0.0 |  | auth_totp and password_security compatibility
[auth_user_case_insensitive](auth_user_case_insensitive/) | 10.0.1.0.1 |  | Makes the user login field case insensitive
[auto_backup](auto_backup/) | 10.0.1.0.2 |  | Backups database
[base_cron_exclusion](base_cron_exclusion/) | 10.0.1.0.0 |  | Allow you to select scheduled actions that should not run simultaneously.
[base_custom_info](base_custom_info/) | 10.0.1.1.0 |  | Add custom field in models
[base_directory_file_download](base_directory_file_download/) | 10.0.1.0.0 |  | Download all files of a directory on server
[base_exception](base_exception/) | 10.0.4.1.1 |  | This module provide an abstract model to manage customizable exceptions to be applied on different models (sale order, invoice, ...)
[base_export_manager](base_export_manager/) | 10.0.1.0.0 |  | Manage model export profiles
[base_export_security](base_export_security/) | 10.0.1.0.0 |  | Security features for Odoo exports
[base_external_dbsource](base_external_dbsource/) | 10.0.2.0.0 |  | External Database Sources
[base_external_dbsource_firebird](base_external_dbsource_firebird/) | 10.0.1.0.0 |  | External Database Source - Firebird
[base_external_dbsource_mssql](base_external_dbsource_mssql/) | 10.0.1.0.0 |  | External Database Source - MSSQL
[base_external_dbsource_mysql](base_external_dbsource_mysql/) | 10.0.1.0.0 |  | External Database Source - MySQL
[base_external_dbsource_odbc](base_external_dbsource_odbc/) | 10.0.1.0.0 |  | External Database Source - ODBC
[base_external_dbsource_oracle](base_external_dbsource_oracle/) | 10.0.1.0.0 |  | External Database Source - Oracle
[base_external_dbsource_sqlite](base_external_dbsource_sqlite/) | 10.0.1.0.0 |  | External Database Source - SQLite
[base_external_system](base_external_system/) | 10.0.1.0.0 |  | Data models allowing for connection to external systems.
[base_fontawesome](base_fontawesome/) | 10.0.4.7.0 |  | Up to date Fontawesome resources.
[base_import_default_enable_tracking](base_import_default_enable_tracking/) | 10.0.1.0.0 |  | This modules simply enables history tracking when doing an import.
[base_import_match](base_import_match/) | 10.0.1.0.0 |  | Try to avoid duplicates before importing
[base_import_odoo](base_import_odoo/) | 10.0.1.0.0 |  | Import records from another Odoo instance
[base_import_security_group](base_import_security_group/) | 10.0.1.0.0 |  | Group-based permissions for importing CSV files
[base_jsonify](base_jsonify/) | 10.0.1.1.0 |  | Base module that provide the jsonify method on all models
[base_kanban_stage](base_kanban_stage/) | 10.0.1.2.1 |  | Provides stage model and abstract logic for inheritance
[base_kanban_stage_state](base_kanban_stage_state/) | 10.0.1.0.0 |  | Maps stages from base_kanban_stage to states
[base_locale_uom_default](base_locale_uom_default/) | 10.0.1.0.0 |  | This provides settings to select default UoMs at the language level.
[base_manifest_extension](base_manifest_extension/) | 10.0.1.0.0 |  | Adds useful keys to manifest files
[base_multi_image](base_multi_image/) | 10.0.1.0.0 |  | Allow multiple images for database objects
[base_onchange_rule](base_onchange_rule/) | 10.0.1.0.0 |  | Define onchange settings for any models
[base_optional_quick_create](base_optional_quick_create/) | 10.0.1.0.1 |  | Avoid 'quick create' on m2o fields, on a 'by model' basis
[base_report_auto_create_qweb](base_report_auto_create_qweb/) | 10.0.1.0.0 |  | Report qweb auto generation
[base_search_fuzzy](base_search_fuzzy/) | 10.0.1.1.0 |  | Fuzzy search with the PostgreSQL trigram extension
[base_suspend_security](base_suspend_security/) | 10.0.1.0.0 |  | Suspend security checks for a call
[base_technical_features](base_technical_features/) | 10.0.1.0.1 |  | Access to technical features without activating debug mode
[base_technical_user](base_technical_user/) | 10.0.1.1.0 |  | Add a technical user parameter on the company
[base_tier_validation](base_tier_validation/) | 10.0.1.0.1 |  | Implement a validation process based on tiers.
[base_user_gravatar](base_user_gravatar/) | 10.0.1.0.1 |  | Synchronize Gravatar Image
[base_user_role](base_user_role/) | 10.0.1.0.3 |  | User roles
[base_user_role_company](base_user_role_company/) | 10.0.1.0.0 |  | User roles by company
[base_view_inheritance_extension](base_view_inheritance_extension/) | 10.0.1.0.2 |  | Adds more operators for view inheritance
[configuration_helper](configuration_helper/) | 10.0.1.0.0 |  | Configuration Helper
[database_cleanup](database_cleanup/) | 10.0.1.0.0 |  | Database cleanup
[date_range](date_range/) | 10.0.3.0.0 | [![lmignon](https://github.com/lmignon.png?size=30px)](https://github.com/lmignon) | Manage all kind of date range
[datetime_formatter](datetime_formatter/) | 10.0.1.0.0 |  | Helper functions to give correct format to date[time] fields
[dbfilter_from_header](dbfilter_from_header/) | 10.0.1.0.0 |  | Filter databases with HTTP headers
[dead_mans_switch_client](dead_mans_switch_client/) | 10.0.1.0.0 |  | Be notified when customers' Odoo instances go down
[disable_odoo_online](disable_odoo_online/) | 10.0.1.0.0 |  | Remove odoo.com Bindings
[fetchmail_attach_from_folder](fetchmail_attach_from_folder/) | 10.0.1.1.0 |  | Attach mails in an IMAP folder to existing objects
[fetchmail_notify_error_to_sender](fetchmail_notify_error_to_sender/) | 10.0.1.0.0 |  | If fetching mails gives error, send an email to sender
[html_image_url_extractor](html_image_url_extractor/) | 10.0.1.0.0 |  | Extract images found in any HTML field
[html_text](html_text/) | 10.0.1.0.1 |  | Generate excerpts from any HTML field
[keychain](keychain/) | 10.0.2.0.2 |  | Store accounts and credentials
[letsencrypt](letsencrypt/) | 10.0.2.0.1 |  | Request SSL certificates from letsencrypt.org
[mail_environment](mail_environment/) | 10.0.1.0.0 |  | Configure mail servers with server_environment_files
[mail_log_message_to_process](mail_log_message_to_process/) | 10.0.1.0.0 |  | Log all messages received, before they start to be processed.
[mass_editing](mass_editing/) | 10.0.2.1.0 |  | Mass Editing
[mass_sorting](mass_sorting/) | 10.0.1.0.0 |  | Sort any models by any fields list
[module_auto_update](module_auto_update/) | 10.0.2.0.3 | [![sbidoul](https://github.com/sbidoul.png?size=30px)](https://github.com/sbidoul) | Automatically update Odoo modules
[module_prototyper](module_prototyper/) | 10.0.1.0.0 |  | Prototype your module.
[onchange_helper](onchange_helper/) | 10.0.3.1.2 |  | Technical module that ease execution of onchange in Python code
[password_security](password_security/) | 10.0.1.1.4 |  | Allow admin to set password security requirements.
[res_config_settings_enterprise_remove](res_config_settings_enterprise_remove/) | 10.0.1.0.0 |  | Remove fields in all settings views marked as enterprise
[save_translation_file](save_translation_file/) | 10.0.1.0.0 |  | Allows developpers to easily generate i18n files
[scheduler_error_mailer](scheduler_error_mailer/) | 10.0.1.0.0 |  | Scheduler Error Mailer
[sentry](sentry/) | 10.0.1.0.1 |  | Report Odoo errors to Sentry
[sequence_check_digit](sequence_check_digit/) | 10.0.1.0.0 |  | Adds a check digit on sequences
[sequence_date_range](sequence_date_range/) | 10.0.1.0.0 |  | Module used to use the year of the date_to into sequences (instead of date_from)
[server_environment](server_environment/) | 10.0.1.3.0 |  | move some configurations out of the database
[server_environment_files_sample](server_environment_files_sample/) | 10.0.1.0.0 |  | sample config file for server_environment
[server_environment_ir_config_parameter](server_environment_ir_config_parameter/) | 10.0.1.0.1 |  | Override System Parameters from server environment file
[slow_statement_logger](slow_statement_logger/) | 10.0.1.0.1 |  | Log slow SQL statements
[sql_export](sql_export/) | 10.0.1.0.0 |  | Export data in csv file with SQL requests
[sql_request_abstract](sql_request_abstract/) | 10.0.1.0.1 |  | Abstract Model to manage SQL Requests
[subscription_action](subscription_action/) | 10.0.1.0.0 |  | Run a server action on a newly created document
[super_calendar](super_calendar/) | 10.0.1.0.0 |  | This module allows to create configurable calendars.
[test_onchange_helper](test_onchange_helper/) | 10.0.2.1.0 |  | Test addon for the onchange_helper addon
[user_immutable](user_immutable/) | 10.0.1.0.0 |  | Add Immutable User Support
[user_threshold](user_threshold/) | 10.0.1.0.1 |  | Add Configurable User Threshold Support
[users_ldap_groups](users_ldap_groups/) | 10.0.0.0.1 |  | Adds user accounts to groups based on rules defined by the administrator.
[users_ldap_mail](users_ldap_mail/) | 10.0.1.0.0 |  | LDAP mapping for user name and e-mail
[users_ldap_populate](users_ldap_populate/) | 10.0.1.0.3 |  | LDAP Populate
[webhook](webhook/) | 10.0.1.0.0 |  | Webhook


Unported addons
---------------
addon | version | maintainers | summary
--- | --- | --- | ---
[admin_technical_features](admin_technical_features/) | 9.0.0.1.0 (unported) |  | Checks the technical features box for admin user.
[auth_from_http_basic](auth_from_http_basic/) | 1.0 (unported) |  | Authenticate via HTTP basic authentication
[auth_from_http_basic_logout](auth_from_http_basic_logout/) | 1.0 (unported) |  | Authenticate via HTTP basic authentication (logout helper)
[auth_from_http_remote_user](auth_from_http_remote_user/) | 8.0.1.0.0 (unported) |  | Authenticate via HTTP Remote User
[email_template_template](email_template_template/) | 1.0 (unported) |  | Templates for email templates
[import_odbc](import_odbc/) | 1.3 (unported) |  | Import data from SQL and ODBC data sources.
[ir_config_parameter_viewer](ir_config_parameter_viewer/) | 0.1 (unported) |  | Ir.config_parameter view
[language_path_mixin](language_path_mixin/) | 8.0.1.0.0 (unported) |  | Setting the partner's language in RML reports
[menu_technical_info](menu_technical_info/) | 9.0.1.0.0 (unported) |  | Fast way to look up technical info about menu item.
[security_protector](security_protector/) | 0.1 (unported) |  | Security protector
[server_env_base_external_referentials](server_env_base_external_referentials/) | 1.0 (unported) |  | Server environment for base_external_referential
[test_configuration_helper](test_configuration_helper/) | 9.0.1.0.0 (unported) |  | Configuration Helper - Tests

[//]: # (end addons)

Translation Status
------------------
[![Transifex Status](https://www.transifex.com/projects/p/OCA-server-tools-10-0/chart/image_png)](https://www.transifex.com/projects/p/OCA-server-tools-10-0)

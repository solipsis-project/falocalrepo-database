# Changelog

### 4.3.0

Removed `JRNN`, `SUBN`, and `USRN` counters from `SETTINGS`.

### 4.2.0

Changes in database functions, simply update `VERSION`.

### 4.0.0

Rename `UDATE` column in `SUBMISSIONS` and `JOURNALS` to `DATE`. Add automatic insertion checks to all tables.

### 3.8.0

Changes in database functions, simply update `VERSION`.

### 3.5.0

Update `HISTORY` entry in `SETTINGS` to use the `List[List[float, str]]` format.

### 3.4.0

Changes in database functions, simply update `VERSION`.

### 3.3.0

Remove `LASTSTART` and `LASTUPDATE` entries and add `HISTORY` entry in `SETTINGS` table.

### 3.2.0

Add `JOURNALS` table and `JOURNALS` field in `USERS` table.

### 3.1.0

`EXTRAS` field in `USERS` table is changed to `MENTIONS`, and `extras` and `Extras` folders are renamed to `mentions` and `mentions_all` respectively.

### 3.0.0

Information from the database are copied over to the new version, but otherwise remain unaltered save for a few changed column names in the `SUBMISSIONS` and `USERS` tables.

Files are moved to the new structure and the old files folder is deleted. Only submissions files are kept starting from version 3.0.0.
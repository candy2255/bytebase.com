- Engine
  - [Require InnoDB](/docs/sql-review/review-rules/supported-rules#engine.mysql.use-innodb)
- Naming
  - [Table naming convention](/docs/sql-review/review-rules/supported-rules#naming.table)
  - [Column naming convention](/docs/sql-review/review-rules/supported-rules#naming.column)
  - [Auto-increment column naming convention](/docs/sql-review/review-rules/supported-rules#naming.column.auto-increment)
  - [Index naming convention](/docs/sql-review/review-rules/supported-rules#naming.index.idx)
  - [Primary key naming convention](/docs/sql-review/review-rules/supported-rules#naming.index.pk)
  - [Unique key naming convention](/docs/sql-review/review-rules/supported-rules#naming.index.uk)
  - [Foreign key naming convention](/docs/sql-review/review-rules/supported-rules#naming.index.fk)
- Statement
  - [Disallow SELECT \*](/docs/sql-review/review-rules/supported-rules#statement.select.no-select-all)
  - [Require WHERE](/docs/sql-review/review-rules/supported-rules#statement.where.require)
  - [Disallow leading % in LIKE](/docs/sql-review/review-rules/supported-rules#statement.where.no-leading-wildcard-like)
  - [Disallow COMMIT](/docs/sql-review/review-rules/supported-rules#statement.disallow-commit)
  - [Disallow LIMIT](/docs/sql-review/review-rules/supported-rules#statement.disallow-limit)
  - [Disallow ORDER BY](/docs/sql-review/review-rules/supported-rules#statement.disallow-order-by)
  - [Merge ALTER TABLE](/docs/sql-review/review-rules/supported-rules#statement.merge-alter-table)
  - [INSERT statements must specify columns](/docs/sql-review/review-rules/supported-rules#statement.insert.must-specify-column)
  - [Disallow ORDER BY RAND in INSERT statements](/docs/sql-review/review-rules/supported-rules#statement.insert.disallow-order-by-rand)
  - [Limit the inserted rows](/docs/sql-review/review-rules/supported-rules#statement.insert.row-limit)
  - [Limit affected rows](/docs/sql-review/review-rules/supported-rules#statement.affected-row-limit)
  - [Dry run DML statements](/docs/sql-review/review-rules/supported-rules#statement.dml-dry-run)
- Table
  - [Require primary key](/docs/sql-review/review-rules/supported-rules#table.require-pk)
  - [Disallow foreign key](/docs/sql-review/review-rules/supported-rules#table.no-foreign-key)
  - [Drop naming convention](/docs/sql-review/review-rules/supported-rules#table.drop-naming-convention)
  - [Disallow partition table](/docs/sql-review/review-rules/supported-rules#table.disallow-partition)
  - [Table comment convention](/docs/sql-review/review-rules/supported-rules#table.comment)
- Schema
  - [Backward incompatible schema change](/docs/sql-review/review-rules/supported-rules#schema.backward-compatibility)
- Column
  - [Enforce the required columns in each table](/docs/sql-review/review-rules/supported-rules#column.required)
  - [Column type disallow list](/docs/sql-review/review-rules/supported-rules#column.disallow-list)
  - [Columns no NULL value](/docs/sql-review/review-rules/supported-rules#column.no-null)
  - [Disallow changing column type](/docs/sql-review/review-rules/supported-rules#column.disallow-change-type)
  - [Set DEFAULT value for NOT NULL columns](/docs/sql-review/review-rules/supported-rules#column.set-default-for-not-null)
  - [Disallow ALTER TABLE CHANGE COLUMN statements](/docs/sql-review/review-rules/supported-rules#column.disallow-change)
  - [Disallow changing column order](/docs/sql-review/review-rules/supported-rules#column.disallow-changing-order)
  - [Use integer for auto-increment columns](/docs/sql-review/review-rules/supported-rules#column.auto-increment-must-integer)
  - [Disallow set charset for columns](/docs/sql-review/review-rules/supported-rules#column.disallow-set-charset)
  - [Set unsigned attribute on auto-increment columns](/docs/sql-review/review-rules/supported-rules#column.auto-increment-must-unsigned)
  - [Column comment convention](/docs/sql-review/review-rules/supported-rules#column.comment)
  - [Maximum CHAR length](/docs/sql-review/review-rules/supported-rules#column.maximum-character-length)
  - [Auto-increment initial value](/docs/sql-review/review-rules/supported-rules#column.auto-increment-initial-value)
  - [Limit the count of current time columns](/docs/sql-review/review-rules/supported-rules#column.current-time-count-limit)
  - [Require column default value](/docs/sql-review/review-rules/supported-rules#column.require-default)
- Index
  - [Disallow duplicate column in index keys](/docs/sql-review/review-rules/supported-rules#index.no-duplicate-column)
  - [Limit the count of index keys](/docs/sql-review/review-rules/supported-rules#index.key-number-limit)
  - [Limit key type for primary keys](/docs/sql-review/review-rules/supported-rules#index.pk-type-limit)
  - [Disallow BLOB and TEXT for index keys](/docs/sql-review/review-rules/supported-rules#index.type-no-blob)
  - [Index count limit](/docs/sql-review/review-rules/supported-rules#index.total-number-limit)
- Database
  - [Drop database restriction](/docs/sql-review/review-rules/supported-rules#database.drop-empty-database)
- System
  - [Charset allow list](/docs/sql-review/review-rules/supported-rules#system.charset.allowlist)
  - [Collation allow list](/docs/sql-review/review-rules/supported-rules#system.collation.allowlist)
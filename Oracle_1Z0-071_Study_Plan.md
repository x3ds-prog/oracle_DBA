# Учебный план: Oracle 1Z0-071 Zero to Hero

Этот документ — наша дорожная карта для подготовки к сертификации Oracle Database SQL Certified Associate (1Z0-071).

**Текущий статус:** ✅ Foundation Level пройден. **Следующая цель:** Условная логика и Работа со временем.

---

### 1. Фундамент и Порядок выполнения (Architecture & Execution)

- [x] **Порядок выполнения (Order of Execution):** - [ПЕРЕЙТИ К УРОКУ](./01_SQL_Fundamentals/02_SQL_Execution_Order.md)
- [x] **NULL во всей красе:** - [ПЕРЕЙТИ К УРОКУ](./01_SQL_Fundamentals/01_First_Queries.md)
- [x] **Сортировка (Sorting):** - [ПЕРЕЙТИ К УРОКУ](./01_SQL_Fundamentals/03_NULL_and_Sorting.md)
- [x] **Ограничение строк:** `WHERE`. - [ПЕРЕЙТИ К УРОКУ](./01_SQL_Fundamentals/02_SQL_Execution_Order.md)
- [x] **Физика базы:** `ROWID`, индексы, Full Scan vs Index Scan. - [ПЕРЕЙТИ К УРОКУ](./03_Database_Internals/02_Physical_Storage_and_ROWID.md)

### 2. Агрегация и Группировка (Aggregation)

- [x] **Групповые функции и Группировка:** - [ПЕРЕЙТИ К УРОКУ](./02_Advanced_SQL/02_Grouping_and_Aggregating_Data.md)
- [x] **Фильтрация групп:** `HAVING` vs `WHERE`. - [ПЕРЕЙТИ К УРОКУ](./02_Advanced_SQL/03_Filtering_Aggregates_with_HAVING.md)

### 3. Соединение таблиц (Joins & Relationships)

- [x] **INNER, LEFT/RIGHT OUTER JOIN, NVL:** - [ПЕРЕЙТИ К УРОКУ](./02_Advanced_SQL/01_Joining_Tables.md)
- [ ] **SELF JOIN:** - [ПЕРЕЙТИ К УРОКУ](./02_Advanced_SQL/04_SELF_JOIN.md)
- [ ] **FULL OUTER JOIN:** - [ПЕРЕЙТИ К УРОКУ](./02_Advanced_SQL/05_FULL_OUTER_JOIN.md)
- [ ] **Cartesian Product (CROSS JOIN):** - [ПЕРЕЙТИ К УРОКУ](./02_Advanced_SQL/06_CROSS_JOIN.md)

### 4. Однострочные функции (Single Row Functions)

- [ ] **Условная логика (Текущая задача):** `CASE` и `DECODE`. - [ПЕРЕЙТИ К УРОКУ](./05_Single_Row_Functions/01_Conditional_Logic_CASE_DECODE.md)
- [ ] **Работа со строками:** `SUBSTR`, `INSTR`, `LPAD/RPAD`, `TRIM`, `REPLACE`. - [ПЕРЕЙТИ К УРОКУ](./05_Single_Row_Functions/02_String_Functions.md)
- [ ] **Работа с числами:** `ROUND`, `TRUNC`, `MOD`. - [ПЕРЕЙТИ К УРОКУ](./05_Single_Row_Functions/03_Number_Functions.md)
- [ ] **Работа с датами (Критично!):** - [ПЕРЕЙТИ К УРОКУ](./05_Single_Row_Functions/04_Date_Functions.md)

### 5. Конвертация типов (Conversion)

- [ ] **Неявная и Явная конвертация:** - [ПЕРЕЙТИ К УРОКУ](./06_Conversion_Functions/01_Conversion_Intro.md)
- [ ] **Функции конвертации:** `TO_CHAR`, `TO_DATE`, `TO_NUMBER`. - [ПЕРЕЙТИ К УРОКУ](./06_Conversion_Functions/02_TO_CHAR_TO_DATE_TO_NUMBER.md)

### 6. Вложенные запросы (Subqueries)

- [ ] **Single-row и Multi-row subqueries:** - [ПЕРЕЙТИ К УРОКУ](./07_Subqueries/01_Single_and_Multi_Row_Subqueries.md)
- [ ] **Correlated Subqueries:** - [ПЕРЕЙТИ К УРОКУ](./07_Subqueries/02_Correlated_Subqueries.md)
- [ ] **EXISTS vs IN:** - [ПЕРЕЙТИ К УРОКУ](./07_Subqueries/03_EXISTS_vs_IN.md)

### 7. Операторы множеств (Set Operators)

- [ ] **UNION / UNION ALL:** - [ПЕРЕЙТИ К УРОКУ](./08_Set_Operators/01_UNION_UNION_ALL.md)
- [ ] **INTERSECT / MINUS:** - [ПЕРЕЙТИ К УРОКУ](./08_Set_Operators/02_INTERSECT_MINUS.md)

### 8. DDL и Объекты схемы (Schema Objects)

- [x] **Таблицы:** `CREATE TABLE`, типы данных. - [ПЕРЕЙТИ К УРОКУ](./00_Introduction_and_Setup/01_Setting_Up_Your_Lab.md)
- [ ] **Constraints (Ограничения):** `PRIMARY KEY`, `FOREIGN KEY`, `NOT NULL`, `CHECK`, `UNIQUE`. - [ПЕРЕЙТИ К УРОКУ](./09_DDL_and_Schema_Objects/01_Constraints.md)
- [ ] **Views (Представления):** - [ПЕРЕЙТИ К УРОКУ](./09_DDL_and_Schema_Objects/02_Views.md)
- [ ] **Sequences & Synonyms:** - [ПЕРЕЙТИ К УРОКУ](./09_DDL_and_Schema_Objects/03_Sequences_and_Synonyms.md)

### 9. DML и Транзакции (Data Manipulation)

- [x] **INSERT / UPDATE / DELETE:** - [ПЕРЕЙТИ К УРОКУ](./02_Advanced_SQL/01_Joining_Tables.md)
- [x] **Транзакции (ACID):** `COMMIT`, `ROLLBACK`. - [ПЕРЕЙТИ К УРОКУ](./03_Database_Internals/01_Transactions_and_COMMIT.md)
- [x] **Concurrency:** Блокировки, `ORA-00054`. - [ПЕРЕЙТИ К УРОКУ](./04_Practical_DBA_Tasks/01_Handling_Locks_and_Concurrency.md)
- [ ] **MERGE:** - [ПЕРЕЙТИ К УРОКУ](./10_DML_and_DCL/01_MERGE.md)

### 10. Управление доступом (DCL)

- [ ] **Пользователи и Привилегии:** `GRANT`, `REVOKE`. - [ПЕРЕЙТИ К УРОКУ](./10_DML_and_DCL/02_Users_and_Privileges.md)
- [ ] **Роли:** - [ПЕРЕЙТИ К УРОКУ](./10_DML_and_DCL/03_Roles.md)

## SQL Table Creation
### Step 1: Image of table to be created
<img width="285" height="164" alt="1" src="https://github.com/user-attachments/assets/355a9cc6-9159-4c97-a9fe-cb92efb064d9" />

### Step 2: Assigned column name and type of entries

```SQL
CREATE TABLE "Sales" (
	"id"	INTEGER,
	"Name"	TEXT,
	"Amount"	INTEGER
);
```

### Step 3: Table formation in SQL

<img width="224" height="119" alt="3" src="https://github.com/user-attachments/assets/3759ef91-5dcd-4613-958c-a1c74355aa5d" />

### Step 4: Inserting values into the table using SQL Query

```SQL
INSERT INTO Sales
(id, Name, Amount)
VALUES
(1, 'Ada', 500),
(2, 'Tunde', 700),
(2, 'Emeka', 300);
```

### Step 5: Final look of the table in SQL

<img width="220" height="180" alt="5" src="https://github.com/user-attachments/assets/0e796cfb-c21c-4890-b61a-bfab22563ec5" />

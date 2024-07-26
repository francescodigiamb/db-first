# DB Car Dealership

table: cars

- id BIGINT PK AI NOTNULL
- brand VARCHAR (20) NOTNULL 
- models VARCHAR (50) NOTNULL
- mileage MEDIUMINT NOTNULL
- year DATE NOTNULL
- fuel VARCHAR (20) NULL
- gearbox VARCHAR (20) NULL
- power SMALLINT NULL
- price DECIMAL (8,2) NULL
- condition VARCHAR (50) NOTNULL
- color VARCHAR (20) NULL
- class VARCHAR (5) NULL
- seat DECIMAL (2,0) NULL
- description TEXT NULL

table: rent

- id BIGINT FK
- id_car 
- name VARCHAR (50)
- surname VARCHAR (50)
- start_rent DATE
- finish_rent DATE
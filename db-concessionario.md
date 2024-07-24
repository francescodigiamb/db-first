# DB Car Dealership

table: Car Dealership

- id BIGINT PK AI NOTNULL
- brand VARCHAR (20) NOTNULL 
- models VARCHAR (50) NOTNULL
- mileage DECIMAL (6,0) NOTNULL
- year DATE NOTNULL
- fuel VARCHAR (20) NULL
- gearbox VARCHAR (20) NULL
- power DECIMAL (3,0) NULL
- price DECIMAL (9,2) NULL
- condition VARCHAR (50) NOTNULL
- class VARCHAR (5) NULL
- seat DECIMAL (2,0) NULL
# Car dealership


| Column | Type | Attributes |
| --- | --- | --- |
| id | BIGINT | PRIMARY_KEY |
| brand | VARCHAR(20) | NOT NULL |
| model | VARCHAR(20) | NOT NULL |
| production_year | DATE | NOT NULL |
| variant | VARCHAR(50) | NULL |
| mileage | INT | NOT NULL |
| price | DECIMAL(10,2) | NOT NULL |
| engine_type | VARCHAR(20) | NOT NULL |
| engine_size | DECIMAL(4,1) | NULL |
| transmission | VARCHAR(20) | NOT NULL |
| fuel_type | VARCHAR(20) | NOT NULL |
| body_type | VARCHAR(20) | NOT NULL |
| color | VARCHAR(20) | NOT NULL |
| number_of_doors | VARCHAR(1) | NOT NULL |
| number_of_seats | VARCHAR(2) | NOT NULL |
| VIN | VARCHAR(17) | UNIQUE |
| license_plate | VARCHAR(10) | UNIQUE |
| date_of_purchase | DATE | NULL |
| last_service_date | DATE | NULL |
| warranty | BOOLEAN | NULL |
| accident_history | BOOLEAN | NULL |
| owner_history_count | INT | NULL |
| location | VARCHAR(50) | NULL |
| status | ENUM('Available', 'Sold', 'Reserved') | NOT NULL |
| photos_URLs | TEXT | NULL |
| description | TEXT | NULL |

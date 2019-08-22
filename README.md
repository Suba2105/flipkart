# flipkart

## Tables

#### Table 1: book
| SNo | Book_Name | Category | Price | Year |
|--|--|--|--|--|
| 1 | Being A Surgeon | Medical | 500 | 2017 |
| 2 | Inorganic Chemistry | Chemistry | 600 | 2016 |
| 3 | Quantum Physics | Physics | 800 | 2018 |

#### Feature 1: List All Books
select * from book;

#### Feature 2: Display Price Low To High
select * from book ORDER BY price asc;

#### Feature 3: Display Price High To Low
select * from book ORDER BY price desc;

#### Feature 4: Display Book based on Chemistry Category
select * from book where category=chemistry;

#### Feature 5: Display Book based on Price Range
select * from book where price between 500 and 1000;   

#### Feature 6: Display Book_Name,Category,Price and year in ascending order
Select Book_Name,Category,Price,Year from book ORDER BY asc;




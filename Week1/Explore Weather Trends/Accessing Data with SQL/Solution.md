SQL Query: "SELECT city_data.year, city_data.city, city_data.country, city_data.avg_temp as avg_local_temp, global_data.avg_temp as avg_global_temp
from city_data
INNER JOIN global_data 
ON city_data.year=global_data.year
WHERE city_data.city='Delhi';"

References:
    - https://towardsdatascience.com/grouping-and-aggregating-data-using-sql-7ac85d654fe4
    - https://towardsdatascience.com/combining-tables-using-sql-f6ddfd5f8b6f

External Courses/Resources:
    - https://www.khanacademy.org/computing/computer-programming/sql
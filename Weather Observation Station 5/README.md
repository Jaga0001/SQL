<h1> Weather Observation Station 5 </h1>

Query the two cities in STATION with the shortest and longest CITY names, as well as their respective lengths (i.e.: number of characters in the name). If there is more than one smallest or largest city, choose the one that comes first when ordered alphabetically.
The STATION table is described as follows

![image](https://github.com/Jaga0001/SQL/assets/144882407/f8f814c7-74b0-4162-b897-0acb5e332f30)

where LAT_N is the northern latitude and LONG_W is the western longitude.

<h2> Sample Input </h2>

`For example, CITY has four entries: DEF, ABC, PQRS and WXY.`

<h2> Sample Output </h2>

```
ABC 3
PQRS 4
```

<h2> Explanation </h2>

When ordered alphabetically, the CITY names are listed as ABC, DEF, PQRS, and WXY, with lengths  and . The longest name is PQRS, but there are  options for shortest named city. Choose ABC, because it comes first alphabetically.

<h2> Note </h2>

You can write two separate queries to get the desired output. It need not be a single query.

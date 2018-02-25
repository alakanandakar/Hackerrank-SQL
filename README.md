# Hackerrank-SQL

SELECT  concat(Name,'(',LEFT(Occupation,1),')') FROM OCCUPATIONS order by name;

select 'There are a total of',count(Occupation), concat(lower(occupation),'s.') from OCCUPATIONS group by Occupation order by count(Occupation) asc, occupation;

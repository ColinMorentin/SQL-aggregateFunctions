/*
SELECT COUNT(*) FROM startups;

SELECT SUM(valuation)
FROM startups;

SELECT MAX(raised)
FROM startups;

SELECT MAX(raised)
FROM startups
WHERE stage == 'Seed';

SELECT MIN(founded) FROM startups;

SELECT AVG(valuation) FROM startups;

SELECT category, AVG(valuation) FROM startups
GROUP BY category;

SELECT category, ROUND(AVG(valuation),2) FROM startups
GROUP BY category;

SELECT category, ROUND(AVG(valuation),2) FROM Startups
GROUP by category
ORDER by ROUND(AVG(valuation),2) DESC;

SELECT category, COUNT(category) FROM startups
GROUP by category;

SELECT category, COUNT(category) FROM startups
GROUP by category
HAVING COUNT(category) > 3;

SELECT location, AVG(employees) FROM Startups
GROUP BY location;
*/

SELECT location, AVG(employees) FROM Startups
GROUP BY location
HAVING AVG(employees) > 500;

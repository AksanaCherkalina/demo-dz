print(connected.execute(
"""
SELECT title, relase_year FROM albums
WHERE relase_year = 2018;
""").fetchall())


print(connected.execute(
"""
SELECT title, duration FROM tracks
ORDER BY duration DESC;
""").fetchall())


print(connected.execute(
"""
SELECT title, length FROM collections
WHERE length >= 3,5;
""").fetchmany(10))


print(connected.execute(
"""
SELECT title, relase_year FROM collections
WHERE relase_year > 2018 AND < 2020;
""").fetchall())


print(connected.execute(
"""
SELECT artist_name FROM artists
WHERE artist_name = 1;
""").fetchall())


print(connected.execute(
"""
SELECT title FROM tracks
WHERE title  LIKE %%мой%%;
""").fetchall())
INSERT INTO generes (ID,NAME)
VALUES (1, 'Электронная музыка' );

INSERT INTO generes (ID,NAME)
VALUES (2, 'Джаз' );

INSERT INTO generes (ID,NAME)
VALUES (3, 'Поп-музыка' );

INSERT INTO generes (ID,NAME)
VALUES (4, 'Рок' );

INSERT INTO generes (ID,NAME)
VALUES (5, 'Диско' );


INSERT INTO artists (ID,NAME)
VALUES (1, 'ATB' );

INSERT INTO artists (ID,NAME)
VALUES (2, 'Depeshe Mode' );

INSERT INTO artists (ID,NAME)
VALUES (3, 'Air' );

INSERT INTO artists (ID,NAME)
VALUES (4, 'Miles Davis' );

INSERT INTO artists (ID,NAME)
VALUES (5, 'Troye Sivan' );

INSERT INTO artists (ID,NAME)
VALUES (6, 'NILETTO' );

INSERT INTO artists (ID,NAME)
VALUES (7, 'Кино' );

INSERT INTO artists (ID,NAME)
VALUES (8, 'Dua Lipa' );


INSERT INTO albums (ID,TITLE,DATE)
VALUES (1, 'No Silence', 2004 );

INSERT INTO albums (ID,TITLE,DATE)
VALUES (2, 'Exciter', 2001 );

INSERT INTO albums (ID,TITLE,DATE)
VALUES (3, 'Talkie Walkie', 2004 );

INSERT INTO albums (ID,TITLE,DATE)
VALUES (4, 'Kind of Blue', 1959 );

INSERT INTO albums (ID,TITLE,DATE)
VALUES (5, 'Bloom', 2018 );

INSERT INTO albums (ID,TITLE,DATE)
VALUES (6, 'Любимка', 2019 );

INSERT INTO albums (ID,TITLE,DATE)
VALUES (7, 'Звезда по имени Солнце', 1989 );

INSERT INTO albums (ID,TITLE,DATE)
VALUES (8, 'Future Nostalgia', 2020 );


INSERT INTO tracks (ID,album_id,TITLE,DURATION)
VALUES (1, 1, 'Marrakech', 00-03-46 );

INSERT INTO tracks (ID,album_id,TITLE,DURATION)
VALUES (2, 1, 'Ecstasy', 00-03-21 );

INSERT INTO tracks (ID,album_id,TITLE,DURATION)
VALUES (3, 1, 'The Autumn Leaves', 00-05-42 );

INSERT INTO tracks (ID,album_id,TITLE,DURATION)
VALUES (4, 2, 'Dream On', 00-04-20 );

INSERT INTO tracks (ID,album_id,TITLE,DURATION)
VALUES (5, 2, 'Shine', 00-05-33 );

INSERT INTO tracks (ID,album_id,TITLE,DURATION)
VALUES (6, 2, 'The Sweetest Condition', 00-03-43 );

INSERT INTO tracks (ID,album_id,TITLE,DURATION)
VALUES (7, 3, 'Venus', 00-04-04 );

INSERT INTO tracks (ID,album_id,TITLE,DURATION)
VALUES (8, 3, 'Cherry Blossom Girl', 00-03-39 );

INSERT INTO tracks (ID,album_id,TITLE,DURATION)
VALUES (9, 3, 'Run', 00-04-12 );

INSERT INTO tracks (ID,album_id,TITLE,DURATION)
VALUES (10, 4, 'So What', 00-09-07 );

INSERT INTO tracks (ID,album_id,TITLE,DURATION)
VALUES (11, 4, 'Freddie Freeloader', 00-09-48 );

INSERT INTO tracks (ID,album_id,TITLE,DURATION)
VALUES (12, 4, 'Blue in Green', 00-05-35 );

INSERT INTO tracks (ID,album_id,TITLE,DURATION)
VALUES (13, 5, 'Seventeen', 00-03-38 );

INSERT INTO tracks (ID,album_id,TITLE,DURATION)
VALUES (14, 5, 'MyMyMy!', 00-03-25 );

INSERT INTO tracks (ID,album_id,TITLE,DURATION)
VALUES (15, 5, 'The Good Side', 00-04-28 );

INSERT INTO tracks (ID,album_id,TITLE,DURATION)
VALUES (16, 6, 'Любимка', 00-03-40 );

INSERT INTO tracks (ID,album_id,TITLE,DURATION)
VALUES (17, 6, 'Любимка, другая', 00-03-17 );

INSERT INTO tracks (ID,album_id,TITLE,DURATION)
VALUES (18, 7, 'Песня без слов', 00-05-03 );

INSERT INTO tracks (ID,album_id,TITLE,DURATION)
VALUES (19, 7, 'Звезда по имени Солнце', 00-03-46 );

INSERT INTO tracks (ID,album_id,TITLE,DURATION)
VALUES (20, 7, 'Невеселая песня', 00-04-15 );

INSERT INTO tracks (ID,album_id,TITLE,DURATION)
VALUES (21, 8, 'Future Nostalgia', 00-03-05 );

INSERT INTO tracks (ID,album_id,TITLE,DURATION)
VALUES (22, 8, 'Dont Start Now', 00-03-03 );

INSERT INTO tracks (ID,album_id,TITLE,DURATION)
VALUES (23, 8, 'Cool', 00-03-30 );


INSERT INTO collections (ID,NAME,DATE)
VALUES (1, '9PmTill', 2021 );

INSERT INTO collections (ID,NAME,DATE)
VALUES (2, 'The Best of Depeche Mode from Bortmehanik', 2021 );

INSERT INTO collections (ID,NAME,DATE)
VALUES (3, 'Forever Love: Greatest Hits от Air Supply', 2005 );

INSERT INTO collections (ID,NAME,DATE)
VALUES (4, 'The Complete On The Corner Sessions', 2007 );

INSERT INTO collections (ID,NAME,DATE)
VALUES (5, 'SUBURBIA', 2015 );

INSERT INTO collections (ID,NAME,DATE)
VALUES (6, 'NILETTO', 2020 );

INSERT INTO collections (ID,NAME,DATE)
VALUES (7, 'Кино', 2020 );

INSERT INTO collections (ID,NAME,DATE)
VALUES (8, 'Club Future Nostalgia', 2020 );


INSERT INTO artistGenres (ID,artist_id,genere_id)
VALUES (1, 1, 1 );

INSERT INTO artistGenres (ID,artist_id,genere_id)
VALUES (2, 2, 1 );

INSERT INTO artistGenres (ID,artist_id,genere_id)
VALUES (3, 3, 1 );

INSERT INTO artistGenres (ID,artist_id,genere_id)
VALUES (4, 4, 2 );

INSERT INTO artistGenres (ID,artist_id,genere_id)
VALUES (5, 5, 3 );

INSERT INTO artistGenres (ID,artist_id,genere_id)
VALUES (6, 6, 3 );

INSERT INTO artistGenres (ID,artist_id,genere_id)
VALUES (7, 7, 4 );

INSERT INTO artistGenres (ID,artist_id,genere_id)
VALUES (8, 8, 5 );


INSERT INTO artistAlbums (ID,artist_id,album_id)
VALUES (1, 1, 1 );

INSERT INTO artistAlbums (ID,artist_id,album_id)
VALUES (2, 2, 2 );

INSERT INTO artistAlbums (ID,artist_id,album_id)
VALUES (3, 3, 3 );

INSERT INTO artistAlbums (ID,artist_id,album_id)
VALUES (4, 4, 4 );

INSERT INTO artistAlbums (ID,artist_id,album_id)
VALUES (5, 5, 5 );

INSERT INTO artistAlbums (ID,artist_id,album_id)
VALUES (6, 6, 6 );

INSERT INTO artistAlbums (ID,artist_id,album_id)
VALUES (7, 7, 7 );

INSERT INTO artistAlbums (ID,artist_id,album_id)
VALUES (8, 8, 8 );


INSERT INTO trackCollections (ID,track_id,collection_id)
VALUES (1, 2, 1 );

INSERT INTO trackCollections (ID,track_id,collection_id)
VALUES (2, 3, 1 );

INSERT INTO trackCollections (ID,track_id,collection_id)
VALUES (3, 4, 2 );

INSERT INTO trackCollections (ID,track_id,collection_id)
VALUES (4, 7, 3 );

INSERT INTO trackCollections (ID,track_id,collektion_id)
VALUES (5, 9, 3 );

INSERT INTO trackCollections (ID,track_id,collektion_id)
VALUES (6, 10, 4 );

INSERT INTO trackCollections (ID,track_id,collektion_id)
VALUES (7, 14, 5 );

INSERT INTO trackCollections (ID,track_id,collektion_id)
VALUES (8, 16, 6 );

INSERT INTO trackCollections (ID,track_id,collektion_id)
VALUES (9, 19, 7 );

INSERT INTO trackCollections (ID,track_id,collektion_id)
VALUES (10, 21, 8 );

INSERT INTO trackCollections (ID,track_id,collektion_id)
VALUES (11, 22, 8 );

INSERT INTO trackCollections (ID,track_id,collektion_id)
VALUES (12, 23, 8 );

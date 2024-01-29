-- phpMyAdmin SQL Dump
-- version 4.9.5deb2
-- https://www.phpmyadmin.net/
--
-- Host: localhost
-- Generation Time: Dec 10, 2023 at 01:27 PM
-- Server version: 10.3.38-MariaDB-0ubuntu0.20.04.1
-- PHP Version: 7.4.3-4ubuntu2.19

SET SQL_MODE = "NO_AUTO_VALUE_ON_ZERO";
SET AUTOCOMMIT = 0;
START TRANSACTION;
SET time_zone = "+00:00";


/*!40101 SET @OLD_CHARACTER_SET_CLIENT=@@CHARACTER_SET_CLIENT */;
/*!40101 SET @OLD_CHARACTER_SET_RESULTS=@@CHARACTER_SET_RESULTS */;
/*!40101 SET @OLD_COLLATION_CONNECTION=@@COLLATION_CONNECTION */;
/*!40101 SET NAMES utf8mb4 */;

--
-- Database: `lmh1_2_db`
--
CREATE DATABASE IF NOT EXISTS `lmh1_2_db` DEFAULT CHARACTER SET utf8mb4 COLLATE utf8mb4_general_ci;
USE `lmh1_2_db`;

-- --------------------------------------------------------

--
-- Table structure for table `AA_BP`
--

DROP TABLE IF EXISTS `AA_BP`;
CREATE TABLE `AA_BP` (
  `AWARD_ID` char(4) NOT NULL,
  `MOVIE_ID` varchar(4) DEFAULT NULL,
  `DIRECTOR_ID` varchar(5) DEFAULT NULL,
  `STUDIO_NAME` varchar(75) DEFAULT NULL,
  `MOVIE_RELEASEYR` year(4) DEFAULT NULL
) ENGINE=InnoDB DEFAULT CHARSET=utf8mb4 COLLATE=utf8mb4_general_ci;

--
-- Dumping data for table `AA_BP`
--

INSERT INTO `AA_BP` (`AWARD_ID`, `MOVIE_ID`, `DIRECTOR_ID`, `STUDIO_NAME`, `MOVIE_RELEASEYR`) VALUES
('AA01', '1002', 'DIR18', 'Metro-Goldwyn-Mayer Studios, Inc', 1959),
('AA02', '1021', 'DIR16', 'United Artists Corporation', 1961),
('AA03', '1011', 'DIR11', 'Colubmia Pictures', 1962),
('AA04', '1017', 'DIR16', '20th Century', 1965),
('AA05', '1016', 'DIR01', 'United Artists Corporation', 1976),
('AA06', '1005', 'DIR07', 'Warner Bros. Pictures', 1981),
('AA07', '1007', 'DIR19', 'Paramount Pictures', 1994),
('AA08', '1012', 'DIR08', 'New Line Cinema', 2003),
('AA09', '1014', 'DIR09', 'A24', 2016);

-- --------------------------------------------------------

--
-- Table structure for table `ACTOR`
--

DROP TABLE IF EXISTS `ACTOR`;
CREATE TABLE `ACTOR` (
  `ACTOR_ID` char(5) NOT NULL,
  `ACTOR_LNAME` varchar(35) DEFAULT NULL,
  `ACTOR_FNAME` varchar(35) DEFAULT NULL,
  `ACTOR_INITAL` char(2) DEFAULT NULL,
  `ACTOR_DOB` date DEFAULT NULL
) ENGINE=InnoDB DEFAULT CHARSET=utf8mb4 COLLATE=utf8mb4_general_ci;

--
-- Dumping data for table `ACTOR`
--

INSERT INTO `ACTOR` (`ACTOR_ID`, `ACTOR_LNAME`, `ACTOR_FNAME`, `ACTOR_INITAL`, `ACTOR_DOB`) VALUES
('ACT02', 'Andrews', 'Julie', NULL, '1935-10-01'),
('ACT03', 'Balsam', 'Martin', NULL, '1919-02-04'),
('ACT04', 'Beymer', 'Richard', NULL, '1938-02-20'),
('ACT05', 'Brando', 'Marlon', NULL, '1924-04-03'),
('ACT06', 'Charleson', 'Ian', NULL, '1949-08-11'),
('ACT07', 'Comingore', 'Dorothy', NULL, '1912-08-24'),
('ACT08', 'Cotton', 'Joseph', NULL, '1905-05-15'),
('ACT09', 'Cross', 'Ben', NULL, '1947-12-16'),
('ACT10', 'de Havilland', ' Olivia', NULL, '1916-07-01'),
('ACT11', 'Gable', ' Clark', NULL, '1901-02-01'),
('ACT12', 'Garland', ' Judy', NULL, '1922-06-10'),
('ACT13', 'Gavin', ' John', NULL, '1931-04-08'),
('ACT14', 'Hackman', ' Gene', NULL, '1930-01-30'),
('ACT15', 'Hanks', ' Tom', NULL, '1956-07-09'),
('ACT16', 'Harvey', ' Laurence', NULL, '1928-10-01'),
('ACT17', 'Henson', ' Taraji', 'P.', '1970-09-11'),
('ACT18', 'Heston', ' Charlton', NULL, '1923-10-04'),
('ACT19', 'Howard', ' Leslie', NULL, '1893-04-03'),
('ACT20', 'Hunter', ' Kim', NULL, '1922-11-12'),
('ACT21', 'Knightley', ' Kiera', NULL, '1985-03-26'),
('ACT22', 'Leigh', ' Vivien', NULL, '1913-11-05'),
('ACT23', 'Leigh', ' Janet', NULL, '1927-07-06'),
('ACT24', 'Leigh', ' Janet', NULL, '1927-07-06'),
('ACT25', 'Mason', ' James', NULL, '1909-05-15'),
('ACT26', 'McAvoy', ' James', NULL, '1979-04-21'),
('ACT27', 'McIntire', ' John', NULL, '1907-06-27'),
('ACT28', 'Miles', ' Vera', NULL, '1929-08-23'),
('ACT29', 'Monae', ' Janelle', NULL, '1985-12-01'),
('ACT30', 'Moore', ' Juanita', NULL, '1914-10-19'),
('ACT31', 'O\'Toole', ' Peter', NULL, '1932-08-02'),
('ACT32', 'Perkins', ' Anthony', NULL, '1932-04-04'),
('ACT33', 'Plummer', ' Christopher', NULL, '1929-12-13'),
('ACT34', 'Rhodes', ' Trevante', NULL, '1990-02-10'),
('ACT35', 'Shire', ' Talia', NULL, '1946-04-25'),
('ACT36', 'Shire', ' Talia', NULL, '1946-04-25'),
('ACT37', 'Sinatra', ' Frank', NULL, '1915-12-12'),
('ACT38', 'Tandy', ' Jessica', NULL, '1909-06-07'),
('ACT39', 'Taylor', ' Rod', NULL, '1930-01-11'),
('ACT40', 'Turner', ' Lana', NULL, '1921-02-08'),
('ACT41', 'Welles', 'Orson', NULL, '1915-05-06'),
('ACT42', 'Williams', ' Robin', NULL, '1951-07-21'),
('ACT43', 'Wood', ' Natalie', NULL, '1938-07-20'),
('ACT44', 'Wood', ' Elijah', NULL, '1981-01-28');

-- --------------------------------------------------------

--
-- Table structure for table `DIRECTOR`
--

DROP TABLE IF EXISTS `DIRECTOR`;
CREATE TABLE `DIRECTOR` (
  `DIRECTOR_ID` char(5) NOT NULL,
  `DIRECTOR_LNAME` varchar(75) DEFAULT NULL,
  `DIRECTOR_FNAME` varchar(50) DEFAULT NULL,
  `DIRECTOR_INITAL` char(2) DEFAULT NULL,
  `DIRECTOR_DOB` date DEFAULT NULL
) ENGINE=InnoDB DEFAULT CHARSET=utf8mb4 COLLATE=utf8mb4_general_ci;

--
-- Dumping data for table `DIRECTOR`
--

INSERT INTO `DIRECTOR` (`DIRECTOR_ID`, `DIRECTOR_LNAME`, `DIRECTOR_FNAME`, `DIRECTOR_INITAL`, `DIRECTOR_DOB`) VALUES
('DIR01', 'Avildsen', 'John', 'G.', '1935-12-21'),
('DIR02', 'Coppola', 'Francis', 'F.', '1939-04-07'),
('DIR03', 'Cukor', 'George', NULL, '1899-07-07'),
('DIR04', 'Fleming', ' Victor', NULL, '1889-02-23'),
('DIR05', 'Frankenheimer', ' John', NULL, '1930-02-19'),
('DIR06', 'Hitchcock', ' Alfred', NULL, '1899-08-13'),
('DIR07', 'Hudson', ' Hugh', NULL, '1936-08-25'),
('DIR08', 'Jackson', ' Peter', NULL, '1961-10-31'),
('DIR09', 'Jenkins', ' Barry', NULL, '1979-11-19'),
('DIR10', 'Kazan', ' Elia', NULL, '1909-09-07'),
('DIR11', 'Lean', ' David', NULL, '1908-03-25'),
('DIR12', 'Melfi', ' Theodore', NULL, '1970-10-27'),
('DIR13', 'Nichols', 'Mike', NULL, '1931-11-06'),
('DIR14', 'Sirk', 'Douglas', NULL, '1897-04-26'),
('DIR15', 'Welles', 'Orson', NULL, '1915-05-06'),
('DIR16', 'Wise', 'Robert', NULL, '1914-09-10'),
('DIR17', 'Wright', 'Joe', NULL, '1972-08-25'),
('DIR18', 'Wyler', 'William', NULL, '1902-07-01'),
('DIR19', 'Zemeckis', ' Robert', NULL, '1952-05-14');

-- --------------------------------------------------------

--
-- Table structure for table `FILM_STREAM`
--

DROP TABLE IF EXISTS `FILM_STREAM`;
CREATE TABLE `FILM_STREAM` (
  `FS_ID` char(5) NOT NULL,
  `FSTREAM_DATE` year(4) DEFAULT NULL,
  `MOVIE_ID` varchar(4) DEFAULT NULL,
  `MOVIE_TITLE` varchar(95) DEFAULT NULL,
  `STREAM_ID` varchar(5) DEFAULT NULL,
  `MOVIE_RELEASEYR` year(4) DEFAULT NULL,
  `DIRECTOR_ID` varchar(5) DEFAULT NULL
) ENGINE=InnoDB DEFAULT CHARSET=utf8mb4 COLLATE=utf8mb4_general_ci;

--
-- Dumping data for table `FILM_STREAM`
--

INSERT INTO `FILM_STREAM` (`FS_ID`, `FSTREAM_DATE`, `MOVIE_ID`, `MOVIE_TITLE`, `STREAM_ID`, `MOVIE_RELEASEYR`, `DIRECTOR_ID`) VALUES
('FS001', 2018, '1007', 'Forrest Gump', 'SID05', 1994, 'DIR19'),
('FS002', 2019, '1015', 'Psycho', 'SID06', 1960, 'DIR06'),
('FS003', 2019, '1005', 'Chariots of Fire', 'SID07', 1981, 'DIR07'),
('FS004', 2019, '1016', 'Rocky', 'SID03', 1976, 'DIR01'),
('FS005', 2019, '1014', 'Moonlight', 'SID03', 2016, 'DIR09'),
('FS006', 2020, '1011', 'Lawrence of Arabia', 'SID06', 1962, 'DIR11'),
('FS007', 2020, '1009', 'Hidden Figures', 'SID02', 2016, 'DIR12'),
('FS008', 2021, '1012', 'Lord of the Rings, The: The Return of the King', 'SID03', 2003, 'DIR08'),
('FS009', 2022, '1008', 'Gone With The Wind', 'SID03', 1939, 'DIR04'),
('FS010', 2022, '1013', 'Manchurian Candidate, The', 'SID01', 1962, 'DIR05'),
('FS011', 2023, '1003', 'Birdcage, The', 'SID01', 1996, 'DIR13');

-- --------------------------------------------------------

--
-- Table structure for table `GG_DMP`
--

DROP TABLE IF EXISTS `GG_DMP`;
CREATE TABLE `GG_DMP` (
  `AWARD_ID` char(4) NOT NULL,
  `MOVIE_ID` varchar(4) DEFAULT NULL,
  `DIRECTOR_ID` varchar(5) DEFAULT NULL,
  `STUDIO_NAME` varchar(75) DEFAULT NULL,
  `MOVIE_RELEASEYR` year(4) DEFAULT NULL
) ENGINE=InnoDB DEFAULT CHARSET=utf8mb4 COLLATE=utf8mb4_general_ci;

--
-- Dumping data for table `GG_DMP`
--

INSERT INTO `GG_DMP` (`AWARD_ID`, `MOVIE_ID`, `DIRECTOR_ID`, `STUDIO_NAME`, `MOVIE_RELEASEYR`) VALUES
('GG01', '1002', 'DIR18', 'Metro-Goldwyn-Mayer Studios, Inc', 1959),
('GG02', '1011', 'DIR11', 'Columbia Pictures', 1962),
('GG03', '1020', 'DIR02', 'Paramount Pictures', 1972);

-- --------------------------------------------------------

--
-- Table structure for table `MOVIE`
--

DROP TABLE IF EXISTS `MOVIE`;
CREATE TABLE `MOVIE` (
  `MOVIE_ID` char(4) NOT NULL,
  `MOVIE_TITLE` varchar(75) DEFAULT NULL,
  `MOVIE_GENRE` varchar(50) DEFAULT NULL,
  `MOVIE_RELEASEYR` year(4) DEFAULT NULL,
  `STUDIO_ID` varchar(4) DEFAULT NULL,
  `DIRECTOR_ID` varchar(5) DEFAULT NULL
) ENGINE=InnoDB DEFAULT CHARSET=utf8mb4 COLLATE=utf8mb4_general_ci;

--
-- Dumping data for table `MOVIE`
--

INSERT INTO `MOVIE` (`MOVIE_ID`, `MOVIE_TITLE`, `MOVIE_GENRE`, `MOVIE_RELEASEYR`, `STUDIO_ID`, `DIRECTOR_ID`) VALUES
('1001', 'Atonement', 'Romance Drama', 2007, '5010', 'DIR17'),
('1002', 'Ben Hur', 'Action', 1959, '5005', 'DIR18'),
('1003', 'Birdcage, The', 'Comedy', 1996, '5005', 'DIR13'),
('1004', 'Birds, The', 'Horror', 1963, '5010', 'DIR06'),
('1005', 'Chariots of Fire', 'Drama', 1981, '5011', 'DIR07'),
('1006', 'Citizen Kane', 'Mystery', 1941, '5008', 'DIR15'),
('1007', 'Forrest Gump', 'Romance Drama', 1994, '5007', 'DIR19'),
('1008', 'Gone With The Wind', 'Romance', 1939, '5005', 'DIR04'),
('1009', 'Hidden Figures', 'Drama', 2016, '5002', 'DIR12'),
('1010', 'Imitation of Life', 'Drama', 1959, '5010', 'DIR14'),
('1011', 'Lawrence of Arabia', 'Drama', 1962, '5004', 'DIR11'),
('1012', 'Lord of the Rings, The: The Return of the King', 'Fantasy', 2003, '5006', 'DIR08'),
('1013', 'Manchurian Candidate, The', 'Thriller ', 1962, '5009', 'DIR05'),
('1014', 'Moonlight', 'Drama', 2016, '5003', 'DIR09'),
('1015', 'Psycho', 'Horror', 1960, '5007', 'DIR06'),
('1016', 'Rocky', 'Drama', 1976, '5009', 'DIR01'),
('1017', 'Sound of Music', 'Musical Drama', 1965, '5002', 'DIR16'),
('1018', 'Star Is Born, A', 'Musical Drama', 1954, '5011', 'DIR03'),
('1019', 'Streetcar Named Desire, A', 'Drama', 1951, '5011', 'DIR10'),
('1020', 'The Godfather', 'Drama', 1972, '5007', 'DIR02'),
('1021', 'West Side Story', 'Musical Drama', 1961, '5009', 'DIR16');

-- --------------------------------------------------------

--
-- Table structure for table `MOVIE_ACT`
--

DROP TABLE IF EXISTS `MOVIE_ACT`;
CREATE TABLE `MOVIE_ACT` (
  `MOVIE_ID` varchar(4) DEFAULT NULL,
  `ACTOR_ID` varchar(5) DEFAULT NULL
) ENGINE=InnoDB DEFAULT CHARSET=utf8mb4 COLLATE=utf8mb4_general_ci;

--
-- Dumping data for table `MOVIE_ACT`
--

INSERT INTO `MOVIE_ACT` (`MOVIE_ID`, `ACTOR_ID`) VALUES
('1001', 'ACT26'),
('1001', 'ACT21'),
('1002', 'ACT18'),
('1003', 'ACT42'),
('1003', 'ACT14'),
('1004', 'ACT39'),
('1004', 'ACT38'),
('1005', 'ACT09'),
('1005', 'ACT06'),
('1006', 'ACT41'),
('1006', 'ACT08'),
('1006', 'ACT07'),
('1007', 'ACT15'),
('1008', 'ACT11'),
('1008', 'ACT22'),
('1008', 'ACT19'),
('1008', 'ACT10'),
('1009', 'ACT17'),
('1009', 'ACT29'),
('1010', 'ACT40'),
('1010', 'ACT30'),
('1010', 'ACT13'),
('1011', 'ACT31'),
('1012', 'ACT44'),
('1013', 'ACT36'),
('1013', 'ACT16'),
('1013', 'ACT23'),
('1014', 'ACT34'),
('1014', 'ACT29'),
('1015', 'ACT32'),
('1015', 'ACT28'),
('1015', 'ACT13'),
('1015', 'ACT03'),
('1015', 'ACT27'),
('1015', 'ACT23'),
('1015', 'ACT27'),
('1015', 'ACT23'),
('1016', 'ACT37'),
('1016', 'ACT35'),
('1017', 'ACT02'),
('1017', 'ACT33'),
('1018', 'ACT12'),
('1018', 'ACT25'),
('1019', 'ACT22'),
('1019', 'ACT05'),
('1019', 'ACT20'),
('1019', 'ACT24'),
('1020', 'ACT05'),
('1021', 'ACT43'),
('1021', 'ACT04');

-- --------------------------------------------------------

--
-- Table structure for table `NEWFIELDS_FP`
--

DROP TABLE IF EXISTS `NEWFIELDS_FP`;
CREATE TABLE `NEWFIELDS_FP` (
  `NEW_PCODE` char(3) NOT NULL,
  `NEW_PDATE` year(4) DEFAULT NULL,
  `MOVIE_ID` char(4) DEFAULT NULL
) ENGINE=InnoDB DEFAULT CHARSET=utf8mb4 COLLATE=utf8mb4_general_ci;

--
-- Dumping data for table `NEWFIELDS_FP`
--

INSERT INTO `NEWFIELDS_FP` (`NEW_PCODE`, `NEW_PDATE`, `MOVIE_ID`) VALUES
('N01', 1978, '1006'),
('N02', 1978, '1008'),
('N03', 1978, '1017'),
('N04', 1979, '1002'),
('N05', 1980, '1018'),
('N06', 1987, '1016'),
('N07', 1994, '1013'),
('N08', 1997, '1013'),
('N09', 1998, '1010'),
('N10', 1999, '1019'),
('N11', 2002, '1004'),
('N12', 2003, '1021'),
('N13', 2004, '1005'),
('N14', 2014, '1020');

-- --------------------------------------------------------

--
-- Table structure for table `SAG_OC`
--

DROP TABLE IF EXISTS `SAG_OC`;
CREATE TABLE `SAG_OC` (
  `AWARD_ID` char(5) NOT NULL,
  `MOVIE_ID` varchar(4) DEFAULT NULL,
  `DIRECTOR_ID` varchar(5) DEFAULT NULL,
  `STUDIO_NAME` varchar(75) DEFAULT NULL,
  `MOVIE_RELEASEYR` year(4) DEFAULT NULL
) ENGINE=InnoDB DEFAULT CHARSET=utf8mb4 COLLATE=utf8mb4_general_ci;

--
-- Dumping data for table `SAG_OC`
--

INSERT INTO `SAG_OC` (`AWARD_ID`, `MOVIE_ID`, `DIRECTOR_ID`, `STUDIO_NAME`, `MOVIE_RELEASEYR`) VALUES
('SAG01', '1003', 'DIR13', 'Metro-Goldwyn-Mayer Studios, Inc', 1993),
('SAG02', '1002', 'DIR08', 'New Line Cinema', 2003),
('SAG03', '1009', 'DIR12', '20th Century Studios', 2016);

-- --------------------------------------------------------

--
-- Stand-in structure for view `SQL Query Two Table`
-- (See below for the actual view)
--
DROP VIEW IF EXISTS `SQL Query Two Table`;
CREATE TABLE `SQL Query Two Table` (
`MOVIE_TITLE` varchar(75)
);

-- --------------------------------------------------------

--
-- Table structure for table `STREAMING`
--

DROP TABLE IF EXISTS `STREAMING`;
CREATE TABLE `STREAMING` (
  `STREAM_ID` char(5) NOT NULL,
  `STREAM_NAME` varchar(50) DEFAULT NULL,
  `STREAM_CITY` varchar(50) DEFAULT NULL,
  `STREAM_STATE` char(2) DEFAULT NULL,
  `STREAM_WEBSITE` varchar(100) DEFAULT NULL
) ENGINE=InnoDB DEFAULT CHARSET=utf8mb4 COLLATE=utf8mb4_general_ci;

--
-- Dumping data for table `STREAMING`
--

INSERT INTO `STREAMING` (`STREAM_ID`, `STREAM_NAME`, `STREAM_CITY`, `STREAM_STATE`, `STREAM_WEBSITE`) VALUES
('SID01', 'Amazon Prime Video', ' Seattle', 'WA', 'https://app.primevideo.com/home'),
('SID02', 'Disney+', 'Los Angeles', 'CA', 'https://www.disneyplus.com/'),
('SID03', 'Max', 'New York City', 'NY', 'https://www.max.com/'),
('SID04', 'Paramount+', 'New York City', 'NY', 'https://www.paramountplus.com/'),
('SID05', 'Pluto TV', 'West Hollywood', 'CA', 'https://pluto.tv/'),
('SID06', 'Sling TV', 'Meridian', 'CO', 'https://www.sling.com/'),
('SID07', 'YouTube', 'San Bruno', 'CA', 'https://www.youtube.com/');

-- --------------------------------------------------------

--
-- Table structure for table `STUDIO`
--

DROP TABLE IF EXISTS `STUDIO`;
CREATE TABLE `STUDIO` (
  `STUDIO_ID` char(4) NOT NULL,
  `STUDIO_NAME` varchar(50) DEFAULT NULL,
  `STUDIO_CITY` varchar(50) DEFAULT NULL,
  `STUDIO_STATE` char(2) DEFAULT NULL,
  `STUDIO_WEBSITE` varchar(90) DEFAULT NULL
) ENGINE=InnoDB DEFAULT CHARSET=utf8mb4 COLLATE=utf8mb4_general_ci;

--
-- Dumping data for table `STUDIO`
--

INSERT INTO `STUDIO` (`STUDIO_ID`, `STUDIO_NAME`, `STUDIO_CITY`, `STUDIO_STATE`, `STUDIO_WEBSITE`) VALUES
('5002', '20th Century Studios, Inc.', 'Los Angeles', 'CA', 'https://www.20thcenturystudios.com/'),
('5003', 'A24', 'New York City', 'NY', 'https://a24films.com/'),
('5004', 'Columbia Pictures', 'Culver City', 'CA', 'https://www.sonypictures.com/'),
('5005', 'Metro-Goldwyn-Mayer Studios, Inc', 'Beverly Hills', 'CA', 'https://mgm.com/'),
('5006', 'New Line Cinema', 'Burbank', 'CA', 'https://www.warnerbros.com/company/divisions/motion-pictures#new-line-cinema'),
('5007', 'Paramount Pictures', 'Hollwyood', 'CA', 'https://www.paramountpictures.com/'),
('5008', 'RKO Radio Pictures, Inc.', 'New York City', 'NY', NULL),
('5009', 'United Artists Corporation', 'Beverly Hills', 'CA', 'https://mgm.com/'),
('5010', 'Universal Pictures', 'Universal City', 'CA', 'https://universalpictures.com/'),
('5011', 'Warner Bros. Pictures', 'Burbank', 'CA', 'https://www.warnerbros.com/movies');

-- --------------------------------------------------------

--
-- Structure for view `SQL Query Two Table`
--
DROP TABLE IF EXISTS `SQL Query Two Table`;

CREATE ALGORITHM=UNDEFINED DEFINER=`lmh1`@`localhost` SQL SECURITY DEFINER VIEW `SQL Query Two Table`  AS  select `MOVIE`.`MOVIE_TITLE` AS `MOVIE_TITLE` from (`MOVIE` join `NEWFIELDS_FP` on(`MOVIE`.`MOVIE_ID` = `NEWFIELDS_FP`.`MOVIE_ID`)) where `MOVIE`.`MOVIE_GENRE` = 'Drama' ;

--
-- Indexes for dumped tables
--

--
-- Indexes for table `AA_BP`
--
ALTER TABLE `AA_BP`
  ADD PRIMARY KEY (`AWARD_ID`),
  ADD KEY `MOVIE_ID` (`MOVIE_ID`),
  ADD KEY `DIRECTOR_ID` (`DIRECTOR_ID`);

--
-- Indexes for table `ACTOR`
--
ALTER TABLE `ACTOR`
  ADD PRIMARY KEY (`ACTOR_ID`);

--
-- Indexes for table `DIRECTOR`
--
ALTER TABLE `DIRECTOR`
  ADD PRIMARY KEY (`DIRECTOR_ID`);

--
-- Indexes for table `FILM_STREAM`
--
ALTER TABLE `FILM_STREAM`
  ADD PRIMARY KEY (`FS_ID`),
  ADD KEY `MOVIE_ID` (`MOVIE_ID`),
  ADD KEY `DIRECTOR_ID` (`DIRECTOR_ID`),
  ADD KEY `STREAM_ID` (`STREAM_ID`) USING BTREE;

--
-- Indexes for table `GG_DMP`
--
ALTER TABLE `GG_DMP`
  ADD PRIMARY KEY (`AWARD_ID`),
  ADD KEY `MOVIE_ID` (`MOVIE_ID`),
  ADD KEY `DIRECTOR_ID` (`DIRECTOR_ID`);

--
-- Indexes for table `MOVIE`
--
ALTER TABLE `MOVIE`
  ADD PRIMARY KEY (`MOVIE_ID`),
  ADD KEY `STUDIO_ID` (`STUDIO_ID`),
  ADD KEY `DIRECTOR_ID` (`DIRECTOR_ID`);

--
-- Indexes for table `MOVIE_ACT`
--
ALTER TABLE `MOVIE_ACT`
  ADD KEY `MOVIE_ID` (`MOVIE_ID`),
  ADD KEY `ACTOR_ID` (`ACTOR_ID`);

--
-- Indexes for table `NEWFIELDS_FP`
--
ALTER TABLE `NEWFIELDS_FP`
  ADD PRIMARY KEY (`NEW_PCODE`),
  ADD KEY `MOVIE_ID` (`MOVIE_ID`);

--
-- Indexes for table `SAG_OC`
--
ALTER TABLE `SAG_OC`
  ADD PRIMARY KEY (`AWARD_ID`),
  ADD KEY `MOVIE_ID` (`MOVIE_ID`),
  ADD KEY `DIRECTOR_ID` (`DIRECTOR_ID`);

--
-- Indexes for table `STREAMING`
--
ALTER TABLE `STREAMING`
  ADD PRIMARY KEY (`STREAM_ID`);

--
-- Indexes for table `STUDIO`
--
ALTER TABLE `STUDIO`
  ADD PRIMARY KEY (`STUDIO_ID`);

--
-- Constraints for dumped tables
--

--
-- Constraints for table `AA_BP`
--
ALTER TABLE `AA_BP`
  ADD CONSTRAINT `AA_BP_ibfk_2` FOREIGN KEY (`DIRECTOR_ID`) REFERENCES `DIRECTOR` (`DIRECTOR_ID`),
  ADD CONSTRAINT `AA_BP_ibfk_3` FOREIGN KEY (`MOVIE_ID`) REFERENCES `MOVIE` (`MOVIE_ID`);

--
-- Constraints for table `FILM_STREAM`
--
ALTER TABLE `FILM_STREAM`
  ADD CONSTRAINT `FILM_STREAM_ibfk_1` FOREIGN KEY (`STREAM_ID`) REFERENCES `STREAMING` (`STREAM_ID`),
  ADD CONSTRAINT `FILM_STREAM_ibfk_2` FOREIGN KEY (`MOVIE_ID`) REFERENCES `MOVIE` (`MOVIE_ID`),
  ADD CONSTRAINT `FILM_STREAM_ibfk_3` FOREIGN KEY (`DIRECTOR_ID`) REFERENCES `DIRECTOR` (`DIRECTOR_ID`);

--
-- Constraints for table `GG_DMP`
--
ALTER TABLE `GG_DMP`
  ADD CONSTRAINT `GG_DMP_ibfk_1` FOREIGN KEY (`MOVIE_ID`) REFERENCES `MOVIE` (`MOVIE_ID`),
  ADD CONSTRAINT `GG_DMP_ibfk_2` FOREIGN KEY (`DIRECTOR_ID`) REFERENCES `DIRECTOR` (`DIRECTOR_ID`);

--
-- Constraints for table `MOVIE`
--
ALTER TABLE `MOVIE`
  ADD CONSTRAINT `MOVIE_ibfk_1` FOREIGN KEY (`STUDIO_ID`) REFERENCES `STUDIO` (`STUDIO_ID`),
  ADD CONSTRAINT `MOVIE_ibfk_2` FOREIGN KEY (`DIRECTOR_ID`) REFERENCES `DIRECTOR` (`DIRECTOR_ID`);

--
-- Constraints for table `MOVIE_ACT`
--
ALTER TABLE `MOVIE_ACT`
  ADD CONSTRAINT `MOVIE_ACT_ibfk_1` FOREIGN KEY (`MOVIE_ID`) REFERENCES `MOVIE` (`MOVIE_ID`),
  ADD CONSTRAINT `MOVIE_ACT_ibfk_2` FOREIGN KEY (`ACTOR_ID`) REFERENCES `ACTOR` (`ACTOR_ID`);

--
-- Constraints for table `NEWFIELDS_FP`
--
ALTER TABLE `NEWFIELDS_FP`
  ADD CONSTRAINT `NEWFIELDS_FP_ibfk_1` FOREIGN KEY (`MOVIE_ID`) REFERENCES `MOVIE` (`MOVIE_ID`);

--
-- Constraints for table `SAG_OC`
--
ALTER TABLE `SAG_OC`
  ADD CONSTRAINT `SAG_OC_ibfk_1` FOREIGN KEY (`MOVIE_ID`) REFERENCES `MOVIE` (`MOVIE_ID`),
  ADD CONSTRAINT `SAG_OC_ibfk_2` FOREIGN KEY (`DIRECTOR_ID`) REFERENCES `DIRECTOR` (`DIRECTOR_ID`);
COMMIT;

/*!40101 SET CHARACTER_SET_CLIENT=@OLD_CHARACTER_SET_CLIENT */;
/*!40101 SET CHARACTER_SET_RESULTS=@OLD_CHARACTER_SET_RESULTS */;
/*!40101 SET COLLATION_CONNECTION=@OLD_COLLATION_CONNECTION */;

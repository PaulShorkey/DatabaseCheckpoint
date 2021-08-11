

![alt text](https://photos.app.goo.gl/buczTgHFyFLWw7vj7)








CREATE TABLE destinations (
  id serial,
  name text,
  average_temp integer,
 cost_of_flight integer,
 has_beaches boolean,
has_mountains boolean
);

INSERT INTO destinations (name, average_temp, cost_of_flight, has_beaches, has_mountains) VALUES ('Thailand', 82, 765, true, true);
INSERT INTO destinations (name, average_temp, cost_of_flight, has_beaches, has_mountains) VALUES ('Minnesota', 41, 235, false, false);
INSERT INTO destinations (name, average_temp, cost_of_flight, has_beaches, has_mountains) VALUES ('New Zealand', 66, 433, true, true);
INSERT INTO destinations (name, average_temp, cost_of_flight, has_beaches, has_mountains) VALUES ('England', 45, 290, false, false);
INSERT INTO destinations (name, average_temp, cost_of_flight, has_beaches, has_mountains) VALUES ('Tristan da Cunha', 59, 1304, true, true);

CREATE TABLE airlines (
  id serial,
  name text
);

INSERT INTO airlines (name) VALUES ('Spirit');
INSERT INTO airlines (name) VALUES ('Lufthansa');
INSERT INTO airlines (name) VALUES ('Delta');
INSERT INTO airlines (name) VALUES ('Southwest');







  
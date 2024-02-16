### Creating Tables

CREATE TABLE posts (
    id INT AUTO_INCREMENT PRIMARY KEY,
    title VARCHAR(255) NOT NULL,
    body TEXT NOT NULL,
    created_at TIMESTAMP DEFAULT CURRENT_TIMESTAMP
);



### Inserting Data

INSERT INTO posts (title, body) VALUES ('Post One', 'This is post one');

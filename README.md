# CakePHP Simple Blog

Created a Simple Blog which contains Title, Article and Timestamp using CakePHP.

## Implementation

Created Articles Database

CREATE TABLE articles (
    id INT UNSIGNED AUTO_INCREMENT PRIMARY KEY,
    title VARCHAR(50),
    body TEXT,
    created DATETIME DEFAULT NULL,
    modified DATETIME DEFAULT NULL
);


Configured database in MAMP

User can add/edit/view and delete articles







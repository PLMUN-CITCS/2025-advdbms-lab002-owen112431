-- Creating tblStudents table
CREATE TABLE tblStudents (
    student_id INT PRIMARY KEY AUTO_INCREMENT,
    student_name VARCHAR(50),
    student_email VARCHAR(50),
    student_phone VARCHAR(50)
);
-- Creating tblStudents table
-- Inserting data into tblStudents
INSERT INTO tblStudents (student_name, student_email, student_phone)
VALUES
    ('John Doe', 'johndoe@gmail.com', '123-456-7890'),
    ('Jane Doe', 'janedoe@gmail.com', '123-456-7890');
SELECT * FROM tblStudents;

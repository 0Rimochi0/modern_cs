INSERT

INSERT INTO profile (id_student, fname, lname, major)
VALUES 
('4561', 'ชื่อเอ', 'นามสกุลเอ', 'วิทยาการคอมพิวเตอร์'),
('4561', 'ชื่อบี', 'นามสกุลบี', 'วิทยาการคอมพิวเตอร์'),
('4561', 'ชื่อซี', 'นามสกุลซี', 'วิทยาการคอมพิวเตอร์');

DELETE

DELETE FROM profile WHERE id_student = '4562'

UPDATE

UPDATE profile SET major = 'คณิตศาสตร์' WHERE id_student = '4563';
git remote add upstream https://gitee.com/mirrors_alibaba/PolarDB-for-PostgreSQL.git

https://gitee.com/mirrors_alibaba/PolarDB-for-PostgreSQL.git



docker run -it \
    -v $PWD:/home/postgres/polardb_pg \
    --shm-size=512m --cap-add=SYS_PTRACE --privileged=true \
    --name polardb_pg_devel \
    polardb/polardb_pg_devel \
    bash
    
CREATE TABLE students (id int, name text) DISTRIBUTED BY (id);
CREATE TABLE classes(id int, classname text, student_id int) DISTRIBUTED BY (id);
INSERT INTO students VALUES (1, 'steven'), (2, 'changchang'), (3, 'guoguo');
INSERT INTO classes VALUES (1, 'math', 1), (2, 'math', 2), (3, 'physics', 3);
SELECT s.name student_name, c.classname FROM students s, classes c WHERE s.id=c.student_id;


gpdb-%Y-%m-%d.csv


call elog_node_display(16, "before 712 root:", root, 1)
call elog_node_display(16, "before 712 joinrel:", joinrel, 1)
call elog_node_display(16, "before 712 outer_rel:", outer_rel, 1)
call elog_node_display(16, "before 712 inner_rel:", inner_rel, 1)

ssh-keygen -t rsa ¨CC ¡°manfuldrifter@hotmail.com¡±

git@github.com:manfuldrifter/test.git

1111
3333

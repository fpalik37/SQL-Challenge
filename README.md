# SQL-Challenge

As a new employee at Pewlett Hackard (don’t let the subtle ‘hack’ reference here fool ya :p), I endeavored a research project which looked at department store personnel employed during the ‘80s and ‘90s (Like, totally awesome! Cowabunga! and Gag me with a park bench! -- all at the same time!)

The research involved a lil’ data modeling, data engineering and analysis 😉. I started the investigation with 6 csv data files, all of which were composed of employee personal and/or department information.

An Entity Relationship Diagram (ERD) was composed in preparation for loading the data into SQL tables.  From the ERD, I was able to capture a schema that then became the architecture from which I established tables.  This required the identification of data types, primary keys, foreign keys and other constraints, along with a sensitivity to ‘table load’ order (i.e. no unanticipated orphans due to ‘relationship-order’ neglect allowed !!) 

Further into my investigation, I created composite keys when one primary key alone was not sufficient to uniquely identify an individual record/row.  These became the necessary link to aggregate data for real-world insight -- just the kinda stuff that gives data gurus their kicks :p.

In the end, I experimented with how to group, order and then display when querying.  I tried to envision how an upper level manager or business consultant might use it, and how best to have the information laid out.  It became a balance between a ‘literal following’ of the task directions and that which looked like the most ergonomic/logical presentation. I’m not sure if I got my rendering to the intended spec, but I did my best without knowing exactly for who and for what the table queries were conducted (i.e., a list of department employees could be organized by department, and then sorted alphabetically within each department – and yet the first column displayed could be dept no., dept. name or even employee name depending on the file use and/or client preference).

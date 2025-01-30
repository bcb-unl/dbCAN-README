Database Installation Command
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

1. We provide command in the run_dbcan script:

.. code-block:: shell

    run_dbcan database --db_dir db

2. Users could also download all  database files from the dbCAN2 website (http://bcb.unl.edu/dbCAN2/download/Databases/), and then put them into the db directory.

.. code-block:: shell

    wget -q https://bcb.unl.edu/dbCAN2/download/test/dbCAN_db.tar.gz -O db.tar.gz
    tar -zxvf db.tar.gz
    rm db.tar.gz

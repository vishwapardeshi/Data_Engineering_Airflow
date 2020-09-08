# Introduction to Apache Airflow

Apache Airflow authors workflows as directed acyclic graphs (DAGs) of tasks. The
airflow scheduler executes your tasks on an array of workers while following the
specified dependencies.

You can interact with Apache Airflow using
1. Rich **command line** utilities make performing complex surgeries on DAGs a snap.
2. Rich **user interface** makes it easy to visualize pipelines running in production, monitor progress, and troubleshoot issues when needed.

Airflow is built using Python but you can execute a program irrespective of the language.

## Using Airflow Webserver
You can start the Airflow webserver using the command line argument:

```airflow webserver -p 9090```

The Airflow UI can be used to examine the DAGs via the following three views:
1. Tree View - lists the tasks and any ordering between them in a tree structure,
with the ability to compress / expand the nodes.
2. Graph View - shows any tasks and their dependencies in a graph structure,
along with the ability to access further details about task runs.
3. Code View - view provides full access to the Python code that makes up the DAG.

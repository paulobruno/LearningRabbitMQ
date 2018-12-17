# "Work queues"

Source tutorial [here](https://www.rabbitmq.com/tutorials/tutorial-two-python.html).

### Running the code

*Terminal 1*
```
$ python3 worker.py
```

*Terminal 2*
```
$ python3 worker.py
```

*Terminal 3*
```
$ python3 new_task.py 1......
$ python3 new_task.py 2......
$ python3 new_task.py 3......
$ python3 new_task.py 4......
$ python3 new_task.py 5......
...
```

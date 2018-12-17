# Topics

Source tutorial [here](https://www.rabbitmq.com/tutorials/tutorial-five-python.html).

### Running the code

*Terminal 1*
```
$ python3 receive_logs_topic.py "#"
```

*Terminal 2*
```
$ python3 receive_logs_topic.py "kern.*"
```

*Terminal 3*
```
$ python3 receive_logs_topic.py "*.critical"
```

*Terminal 3*
```
$ python3 emit_log_topic.py "test.test" "Hello!"
$ python3 emit_log_topic.py "kern.test" "Kern."
$ python3 emit_log_topic.py "test.critical" "Critical"
$ python3 emit_log_topic.py "kern.critical" "Kern Critical"
$ python3 emit_log_topic.py "test.test.test.test.test." "Ahhhhh"
```

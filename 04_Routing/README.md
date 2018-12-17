# Routing

Source tutorial [here](https://www.rabbitmq.com/tutorials/tutorial-four-python.html).

### Running the code

*Terminal 1*
```
$ python3 receive_logs_direct.py error warning
```

*Terminal 2*
```
$ python3 receive_logs_direct.py info warning
```

*Terminal 3*
```
$ python3 emit_log_direct.py error "ERROR!"
$ python3 emit_log_direct.py info "Info"
$ python3 emit_log_direct.py warning "Warning!"
```

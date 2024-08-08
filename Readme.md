## Monitor CPU usage
```bash
[perfmon://CPU Load]
interval = 10
object = Processor
counters = % Processor Time;% User Time
instances = _Total
index = softmania_windows_monitoring_idx
```

## Monitor Memory usage
```bash
[perfmon://Available Memory]
interval = 10
object = Memory
counters = Available Bytes
index = softmania_windows_monitoring_idx
```

## Monitor Disk usage
```bash
[perfmon://Free Disk Space]
interval = 60
object = LogicalDisk
counters = Free Megabytes;% Free Space
instances = _Total
index = softmania_windows_monitoring_idx
```


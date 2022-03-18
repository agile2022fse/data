## This is the data repository for "AgileCtrl: A self-adpative Framework for Configuration Tuning" paper


### outline.xlsx
Overall data from the paper 

### data.tar.gz
supplementary data mentioned in **outline.xlsx**. 

The data format for each benchmark: 
- ca6059: requestSize, usedMem, memLimit, config,timeStamp, DebugInfo, DebugInfo, GOAL, alpha, DebugInfo, DebugInfo, DebugInfo, DebugInfo, DebugInfo, DebugInfo
- hb2149: timeStamp, worstLatency, config, newConfig, numViolations, GOAL, alpha, DebugInfo
- hb3813: callSize, timeStamp, currQueueSize, QueueLimit, usedMem, DebugInfo, DebugInfo, DebugInfo, MemoryLimit, DebugInfo, alpha, DebugInfo, DebugInfo, pid, DebugInfo, DebugInfo, DebugInfo
- hb6728: DebugInfo, timeStamp,usedMem,confLimit,conf,DebugInfo,DebugInfo, Goal, DebugInfo, DebugInfo, DebugInfo, DebugInfo, DebugInfo, alpha,requestSize
- hd4995: timeStamp, Goal, tailLatency, newConfig, Config, duLatency, DebugInfo



The structure of compressed directory looks as follows.
```

.
├── ca6059
│   ├── limit
│   │   ├── agile
│   │   │   ├── high
│   │   │   │   └── d_memory.log
│   │   │   └── low
│   │   │       └── d_memory.log
│   │   ├── kf
│   │   │   ├── high
│   │   │   │   └── d_memory.log
│   │   │   └── low
│   │   │       └── d_memory.log
│   │   ├── olr
│   │   │   ├── high
│   │   │   │   └── d_memory.log
│   │   │   └── low
│   │   │       └── d_memory.log
│   │   └── smartconf
│   │       ├── high
│   │       │   └── d_memory.log
│   │       └── low
│   │           └── d_memory.log
│   └── overall
│       ├── agile
│       │   ├── x1
│       │   │   └── d_memory.log
│       │   ├── x10
│       │   │   └── d_memory.log
│       │   ├── x2
│       │   │   └── d_memory.log
│       │   └── x5
│       │       └── d_memory.log
│       ├── kf
│       │   ├── x1
│       │   │   └── d_memory.log
│       │   ├── x10
│       │   │   └── d_memory.log
│       │   ├── x2
│       │   │   └── d_memory.log
│       │   └── x5
│       │       └── d_memory.log
│       ├── olr
│       │   ├── x1
│       │   │   └── CRASHED
│       │   ├── x10
│       │   │   └── CRASHED
│       │   ├── x2
│       │   │   └── CRASHED
│       │   └── x5
│       │       └── CRASHED
│       └── smartconf
│           ├── x1
│           │   └── d_memory.log
│           ├── x10
│           │   └── CRASHED
│           ├── x2
│           │   └── d_memory.log
│           └── x5
│               └── CRASHED
├── hb2149
│   ├── limit
│   │   ├── agile
│   │   │   ├── high
│   │   │   │   └── onlineInfo.log
│   │   │   └── low
│   │   │       └── onlineInfo.log
│   │   ├── kf
│   │   │   ├── high
│   │   │   │   └── onlineInfo.log
│   │   │   └── low
│   │   │       └── onlineInfo.log
│   │   ├── olr
│   │   │   ├── high
│   │   │   │   └── NO_CONVERGENCE
│   │   │   └── low
│   │   │       └── NO_CONVERGENCE
│   │   └── smartconf
│   │       ├── high
│   │       │   └── onlineInfo.log
│   │       └── low
│   │           └── onlineInfo.log
│   └── overall
│       ├── agile
│       │   ├── x1
│       │   │   └── onlineInfo.log
│       │   ├── x10
│       │   │   └── onlineInfo.log
│       │   ├── x2
│       │   │   └── onlineInfo.log
│       │   └── x5
│       │       └── onlineInfo.log
│       ├── kf
│       │   ├── x1
│       │   │   └── onlineInfo.log
│       │   ├── x10
│       │   │   └── NO_CONVERGENCE
│       │   ├── x2
│       │   │   └── onlineInfo.log
│       │   └── x5
│       │       └── onlineInfo.log
│       ├── olr
│       │   ├── x1
│       │   │   └── NO_CONVERGENCE
│       │   ├── x10
│       │   │   └── NO_CONVERGENCE
│       │   ├── x2
│       │   │   └── NO_CONVERGENCE
│       │   └── x5
│       │       └── NO_CONVERGENCE
│       └── smartconf
│           ├── x1
│           │   └── onlineInfo.log
│           ├── x10
│           │   └── NO_CONVERGENCE
│           ├── x2
│           │   └── onlineInfo.log
│           └── x5
│               └── NO_CONVERGENCE
├── hb3813
│   ├── limit
│   │   ├── agile
│   │   │   ├── high
│   │   │   │   └── EnqueueRate.log.19358
│   │   │   └── low
│   │   │       └── EnqueueRate.log.12851
│   │   ├── kf
│   │   │   ├── high
│   │   │   │   └── EnqueueRate.log.158212
│   │   │   └── low
│   │   │       └── EnqueueRate.log.90125
│   │   ├── olr
│   │   │   ├── high
│   │   │   │   └── CRASHED
│   │   │   └── low
│   │   │       └── CRASHED
│   │   └── smartconf
│   │       ├── high
│   │       │   └── EnqueueRate.log
│   │       └── low
│   │           └── EnqueueRate.log
│   ├── motivation
│   │   ├── EnqueueRate.log.10MB
│   │   ├── EnqueueRate.log.1MB
│   │   ├── EnqueueRate.log.2MB
│   │   └── EnqueueRate.log.5MB
│   └── overall
│       ├── agile
│       │   ├── 1
│       │   │   └── EnqueueRate.log.581
│       │   ├── 10
│       │   │   └── EnqueueRate.log.160226
│       │   ├── 2
│       │   │   └── EnqueueRate.log.191911
│       │   └── 5
│       │       └── EnqueueRate.log.175786
│       ├── kf
│       │   ├── 1
│       │   │   └── EnqueueRate.log.70015
│       │   ├── 10
│       │   │   └── CRASHED
│       │   ├── 2
│       │   │   └── EnqueueRate.log.74877
│       │   └── 5
│       │       └── EnqueueRate.log.79744
│       ├── olr
│       │   ├── 1
│       │   │   └── CRASHED
│       │   ├── 10
│       │   │   └── CRASHED
│       │   ├── 2
│       │   │   └── CRASHED
│       │   └── 5
│       │       └── CRASHED
│       └── smartconf
│           ├── x1
│           │   └── EnqueueRate.log -> ../../../motivation/EnqueueRate.log.1MB
│           ├── x10
│           │   └── EnqueueRate.log.10MB
│           ├── x2
│           │   └── EnqueueRate.log.2MB
│           └── x5
│               └── EnqueueRate.log.5MB
├── hb6728
│   ├── limit
│   │   ├── agile
│   │   │   ├── high
│   │   │   │   └── onlineInfo.log
│   │   │   └── low
│   │   │       └── onlineInfo.log
│   │   ├── kf
│   │   │   ├── high
│   │   │   │   └── onlineInfo.log
│   │   │   └── low
│   │   │       └── onlineInfo.log
│   │   ├── olr
│   │   │   ├── high
│   │   │   │   └── CRASHED
│   │   │   └── low
│   │   │       └── CRASHED
│   │   └── smartconf
│   │       ├── high
│   │       │   └── onlineInfo.log
│   │       └── low
│   │           └── onlineInfo.log
│   └── overall
│       ├── agile
│       │   ├── 1
│       │   │   └── onlineInfo.log
│       │   ├── 10
│       │   │   └── CRASHED
│       │   ├── 2
│       │   │   └── onlineInfo.log
│       │   └── 5
│       │       └── onlineInfo.log
│       ├── kf
│       │   ├── 1
│       │   │   └── onlineInfo.log
│       │   ├── 10
│       │   │   └── onlineInfo.log
│       │   ├── 2
│       │   │   └── onlineInfo.log
│       │   └── 5
│       │       └── onlineInfo.log
│       ├── olr
│       │   ├── 1
│       │   │   └── CRASHED
│       │   ├── 10
│       │   │   └── CRASHED
│       │   ├── 2
│       │   │   └── CRASHED
│       │   └── 5
│       │       └── CRASHED
│       └── smartConf
│           ├── x1
│           │   └── onlineInfo.log
│           ├── x10
│           │   └── CRASHED
│           ├── x2
│           │   └── onlineInfo.log
│           └── x5
│               └── CRASHED
├── hd4995
│   ├── limit
│   │   ├── agile
│   │   │   ├── high
│   │   │   │   └── ControllerAction.log
│   │   │   └── low
│   │   │       └── ControllerAction.log
│   │   ├── kf
│   │   │   ├── high
│   │   │   │   └── ControllerAction.log
│   │   │   └── low
│   │   │       └── ControllerAction.log
│   │   ├── olr
│   │   │   ├── high
│   │   │   │   └── ControllerAction.log
│   │   │   └── low
│   │   │       └── ControllerAction.log
│   │   └── smartconf
│   │       ├── high
│   │       │   └── ControllerAction.log
│   │       └── low
│   │           └── ControllerAction.log
│   ├── motivation -> overall/smartconf/
│   └── overall
│       ├── agile
│       │   ├── 1
│       │   │   └── ControllerAction.log
│       │   ├── 10
│       │   │   └── ControllerAction.log
│       │   ├── 2
│       │   │   └── ControllerAction.log
│       │   └── 5
│       │       └── ControllerAction.log
│       ├── kf
│       │   ├── 1
│       │   │   └── ControllerAction.log
│       │   ├── 10
│       │   │   └── ControllerAction.log
│       │   ├── 2
│       │   │   └── ControllerAction.log
│       │   └── 5
│       │       └── ControllerAction.log
│       ├── olr
│       │   ├── 1
│       │   │   └── ControllerAction.log
│       │   ├── 10
│       │   │   └── ControllerAction.log
│       │   ├── 2
│       │   │   └── ControllerAction.log
│       │   └── 5
│       │       └── ControllerAction.log
│       └── smartconf
│           ├── x1
│           │   └── ControllerAction.log.100cpu
│           ├── x10
│           │   └── ControllerAction.log.10cpu
│           ├── x2
│           │   └── ControllerAction.log.50cpu
│           └── x5
│               └── ControllerAction.log.20cpu
└── README
```


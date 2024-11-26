---
title: WindowsCPUAndMemoryAffinity
content_type: feature_gate

_build:
  list: never
  render: false

stages:
  - stage: alpha 
    defaultValue: false
    fromVersion: "1.32"
---

Add CPU and Memory Affinity support to Windows nodes with [CPUManager](/docs/tasks/administer-cluster/cpu-management-policies/#windows-support),
[MemoryManager](/docs/tasks/administer-cluster/memory-manager/#windows-support)
and topology manager.
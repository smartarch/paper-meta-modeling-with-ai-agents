# Companion Package: Meta-Model-First Development with AI Coding Agents

This repository contains the companion materials for the paper:

**"Meta-Model-First Development with AI Coding Agents"**

## Overview

The package demonstrates the concept of **semi-formal meta-models**, where:
- structural aspects are captured using a conventional EMF/Xcore meta-model
- selected attributes (e.g., `description`) contain natural-language content
- these attributes are augmented with **meta-model-level instructions** for AI agents

These instructions guide:
- co-authoring (how descriptions should be written)
- review (how they should be validated)
- generation (how they influence downstream artifacts such as code)

## Structure

```
meta-model/
    espidf.xcore        # Semi-formal meta-model (EMF Xcore)

model/                  # Example component specifications (an instance of the meta-model)
    heartbeat.yaml
    heartbeat_status.yaml
    http_server.yaml
    wifi_manager.yaml   
```

---
id: version-0.65.0-pre-asf-org.apache.streampipes.processors.enricher.jvm.sizemeasure
title: Size Measure
sidebar_label: Size Measure
original_id: org.apache.streampipes.processors.enricher.jvm.sizemeasure
---



<p align="center"> 
    <img src="/docs/img/pipeline-elements/org.apache.streampipes.processors.enricher.jvm.sizemeasure/icon.png" width="150px;" class="pe-image-documentation"/>
</p>

***

## Description

Measures the size of an incoming event and appends this number to the event by serializing it.

***

## Required input
The size measure processor does not have any specific input requirements.

***

## Configuration

You can specify if the size should be in Bytes, Kilobytes (1024 Bytes) or in Megabytes (1024 Kilobytes).

## Output
The size measure processor appends the size of the event (without the field, which is getting added) as a double. The rest of the event stays the same.
﻿---
title: "Configurable Object"
url: /mmom/configurable-object/
#toc-level: 1
description: "Configurable Object of MMOM Platform."
frontpage_featured: true
weight: 20
aliases:
    - /mmom/configurable-object/index.html
#If moving or renaming this doc file, implement a temporary redirect and let the respective team know they should update the URL in the product. See Mapping to Products for more details.
---

This is the [Module MOM Platform](/mmom/) Configurable Object:

The ‘Configurable Object’ 

![](Aspose.Words.501e9b46-196f-4152-b388-3bfe53b61b9f.002.png)

The ‘Configurable Object’ is composed of: 

- **Fields**: These define the ‘properties’ of the object. There are several predefined types of ‘Field’ definitions that can be used to define the properties on an object. 
- **Methods**: The logic associated with the objects are defined as methods like in any Object-Oriented programming language 
- **Event Handlers**: Every ‘Configurable Object’ has a set of pre-defined object life-cycle related events that are automatically fired by the system during the life of an object based on some external or internal triggers. Event-Handlers are the logic blocks that could be associated to these built-in event types. These event handlers get executed when these ‘events’ are fired during the life of an object instance.
- **Field Event-Handlers**: The ‘Fields’ also have some pre-defined life-cycle events that are fired by the system on external of internal triggers like in the case of an object. Event handlers, logic block, can be associated to these events to configure any logic to be executed when these events are fired.
- **Attributes**: These define additional characteristics that could be related to the aspects that are either used at the ‘design’ time by the configuration tools or behavioral aspects that could take effect at the system runtime. These ‘Attributes’ can be defined both at the ‘Configurable Object’ level and at the ‘Field’ level as well. Examples include: ‘Description’ – which describes the item, ‘Category’ – which puts the object into a particular group which could be used by the configuration tools, ‘Cache-able’ – which defines if this the instances of this object could be cached by the system at runtime, etc. ‘Attributes’ are further classified into 2 categories:
- **Overridable –** these attributes can be overridden by the sub-classes or by customizations 
- **Non-Overridable –** these attributes are NOT allowed to be overridden by the sub-classes or by customizations 
- **Persistence Options**: These provide the ORM mapping to facilitate the object instance to be persisted into a database storage (more details in separate section…)


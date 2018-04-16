---

title: Dimension priority and dimension context for resolution
description: 
author: MargoC
manager: AnnBe
ms.date: 4/16/2018
ms.topic: article
ms.prod: 
ms.service: business-applications
ms.technology: 
ms.author: margoc
audience: Admin

---
#### Dimension priority and dimension context for resolution 

For each pricing dimension, it is now possible to assign a priority by cost,
purchase, sales, or other context defined by the system administrator. The
pricing API runs recursively to match input dimensions to price setup in order
of dimension priority, defaulting to zero only in a no-match scenario.
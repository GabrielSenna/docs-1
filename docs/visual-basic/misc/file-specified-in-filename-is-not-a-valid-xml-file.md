---
title: "File specified in FileName is not a valid XML file | Microsoft Docs"
ms.custom: ""
ms.date: "2015-07-20"
ms.prod: "visual-studio-dev14"
ms.reviewer: ""
ms.suite: ""
ms.technology: 
  - "devlang-visual-basic"
ms.tgt_pltfrm: ""
ms.topic: "article"
ms.assetid: c4c30bf3-e0ad-4bc8-89e0-2c3e49e9793b
caps.latest.revision: 12
author: "stevehoag"
ms.author: "shoag"
manager: "wpickett"
translation.priority.ht: 
  - "de-de"
  - "es-es"
  - "fr-fr"
  - "it-it"
  - "ja-jp"
  - "ko-kr"
  - "ru-ru"
  - "zh-cn"
  - "zh-tw"
translation.priority.mt: 
  - "cs-cz"
  - "pl-pl"
  - "pt-br"
  - "tr-tr"
---
# File specified in FileName is not a valid XML file
The file name that you supplied is not a valid XML file. To specify the allowed structure and content of an XML document, you can use a Document Type Definition (DTD), a Microsoft XML-Data Reduced (XDR) schema, or an XML Schema definition language (XSD) schema. XSD schemas are the preferred way to specify XML grammars in the [!INCLUDE[dnprdnshort](../../csharp/getting-started/includes/dnprdnshort_md.md)].  
  
> [!NOTE]
>  In some earlier versions of Visual Studio, the **XML Designer** is the designer for typed datasets and XML schema. The **XML Designer** can still be used to create and edit XML schema files. However, in [!INCLUDE[vs_current_long](../../csharp/misc/includes/vs_current_long_md.md)], the designer for creating and editing typed datasets is the **Dataset Designer**. For more information, see [Creating and Editing Typed Datasets](https://docs.microsoft.com/visualstudio/data-tools/creating-and-editing-typed-datasets).  
  
## To correct this error  
  
-   Check that you are supplying the correct file name.  
  
-   Check that the specified file contains valid XML by loading the XML file that you want to check into the **XML Designer**. From the **XML** menu, click **Validate XML**. Errors are displayed in the **Task List**.  
  
-   If the XML file has an associated XML Schema, check that the elements appear in the defined structure and that the content of the individual elements conforms to the declared data types specified in the schema.  
  
## See Also  
 <xref:System.Xml>   
 [How to: Parse File Paths](../../visual-basic/developing-apps/programming/drives-directories-files/how-to-parse-file-paths.md)
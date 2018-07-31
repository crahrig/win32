---
Description: A callback that notifies the host of pipeline stages image information returned by the assocaited request.
MS-HAID: vspixengine.IPipeLineStagesCallback\_ResultCallback\_PipeLineStagesID\_EventID\_DWORD\_DWORD\_DWORD\_DWORD\_BYTE\_arr
MSHAttr:
- PreferredSiteName:MSDN
- PreferredLib:/library/windows/desktop
title: IPipeLineStagesCallback::ResultCallback method
ms.technology: desktop
ms.prod: windows
ms.author: windowssdkdev
ms.topic: article
ms.date: 05/31/2018
---

# <span id="vspixengine.ipipelinestagescallback_resultcallback_pipelinestagesid_eventid_dword_dword_dword_dword_byte_arr"></span>IPipeLineStagesCallback::ResultCallback method

A callback that notifies the host of pipeline stages image information returned by the assocaited request.

## Syntax


```C++
);
```

## Parameters

*stageId*   
The pipeline stage represented in the results.

*eid*   
The event represented in the results.

*width*   
The width of the pipeline visualization image.

*height*   
The height of the pipeline visualization image.

*format*   
The format of the pipeline visualization image.

*size*   
The size of the image in bytes.

*count5\_buffer*   
The pipeline visualization image.

## Return value

If this method succeeds, it returns **S\_OK**. Otherwise, it returns an **HRESULT** error code.

## Requirements

<table><colgroup><col style="width: 50%" /><col style="width: 50%" /></colgroup><tbody><tr class="odd"><td><p>Header</p></td><td>Vspixengine.h</td></tr></tbody></table>

## <span id="see_also"></span>See also

[**IPipeLineStagesCallback**](https://msdn.microsoft.com/library/windows/desktop/mt432716)

 

 



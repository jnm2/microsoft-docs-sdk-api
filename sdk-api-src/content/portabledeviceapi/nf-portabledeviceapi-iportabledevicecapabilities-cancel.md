---
UID: NF:portabledeviceapi.IPortableDeviceCapabilities.Cancel
title: IPortableDeviceCapabilities::Cancel (portabledeviceapi.h)
description: The Cancel method cancels a pending request on this interface.
helpviewer_keywords: ["Cancel","Cancel method [Windows Portable Devices SDK]","Cancel method [Windows Portable Devices SDK]","IPortableDeviceCapabilities interface","IPortableDeviceCapabilities interface [Windows Portable Devices SDK]","Cancel method","IPortableDeviceCapabilities.Cancel","IPortableDeviceCapabilities::Cancel","IPortableDeviceCapabilitiesCancel","portabledeviceapi/IPortableDeviceCapabilities::Cancel","wpdsdk.iportabledevicecapabilities_cancel"]
old-location: wpdsdk\iportabledevicecapabilities_cancel.htm
tech.root: wpdsdk
ms.assetid: 5883f855-826c-405f-939f-b2d28548c931
ms.date: 12/05/2018
ms.keywords: Cancel, Cancel method [Windows Portable Devices SDK], Cancel method [Windows Portable Devices SDK],IPortableDeviceCapabilities interface, IPortableDeviceCapabilities interface [Windows Portable Devices SDK],Cancel method, IPortableDeviceCapabilities.Cancel, IPortableDeviceCapabilities::Cancel, IPortableDeviceCapabilitiesCancel, portabledeviceapi/IPortableDeviceCapabilities::Cancel, wpdsdk.iportabledevicecapabilities_cancel
req.header: portabledeviceapi.h
req.include-header: 
req.target-type: Windows
req.target-min-winverclnt: 
req.target-min-winversvr: 
req.kmdf-ver: 
req.umdf-ver: 
req.ddi-compliance: 
req.unicode-ansi: 
req.idl: 
req.max-support: 
req.namespace: 
req.assembly: 
req.type-library: 
req.lib: PortableDeviceGUIDs.lib
req.dll: 
req.irql: 
targetos: Windows
req.typenames: 
req.redist: 
ms.custom: 19H1
f1_keywords:
 - IPortableDeviceCapabilities::Cancel
 - portabledeviceapi/IPortableDeviceCapabilities::Cancel
dev_langs:
 - c++
topic_type:
 - APIRef
 - kbSyntax
api_type:
 - COM
api_location:
 - PortableDeviceGUIDs.lib
 - PortableDeviceGUIDs.dll
api_name:
 - IPortableDeviceCapabilities.Cancel
---

# IPortableDeviceCapabilities::Cancel


## -description

The <b>Cancel</b> method cancels a pending request on this interface.

## -parameters

## -returns

The method returns an <b>HRESULT</b>. Possible values include, but are not limited to, those in the following table.
          

<table>
<tr>
<th>Return code</th>
<th>Description</th>
</tr>
<tr>
<td width="40%">
<dl>
<dt><b>S_OK</b></dt>
</dl>
</td>
<td width="60%">
The method succeeded.

</td>
</tr>
</table>

## -remarks

This method cancels all pending operations on the current device handle, which corresponds to a session associated with an <a href="/windows/desktop/api/portabledeviceapi/nn-portabledeviceapi-iportabledevice">IPortableDevice</a> interface. The Windows Portable Devices (WPD) API does not support targeted cancellation of specific operations.

## -see-also

<a href="/windows/desktop/api/portabledeviceapi/nn-portabledeviceapi-iportabledevicecapabilities">IPortableDeviceCapabilities Interface</a>
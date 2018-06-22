# MCOP SDK version 0.1

<p align="center"><a href="https://mcopenplatform.org" target="_blank" rel="noopener noreferrer"><img src="https://demo.mcopenplatform.org/gitlist/mcop/MCOP-SDK.git/raw/master/images/logoMCOP_MD_w400px.png" alt="MCOP logo"></a></p>

The MCOP MCPTT Client comprises different elements connected by Android’s binder mechanism including the MCPTT Client GUI, the MCOP SDK (responsible of MCPTT protocols) and low level plugins to access SIM card, eMBMS, connectivity and configuration-oam to be deployed to get access to Mission Critical capabilities.

* Refer to [**MCOP SDK** Installation](https://demo.mcopenplatform.org/gitlist/mcop/MCOP-SDK.git/blob/master/docs/MCOP_SDK_Installation.md) for detailed installation and testing steps. The [MCOP MCPTT App Development](https://demo.mcopenplatform.org/gitlist/mcop/MCOP-SDK.git/blob/master/docs/MCOP_App_developing_steps.md) guide provides more info on app development using the MCOP SDK.

* The [**MCOP MCPTT Client**](https://demo.mcopenplatform.org/gitlist/mcop/MCOP-MCPTT-Client.git/blob/master/README.md) that uses the MCOP SDK is also available to download.

License terms are defined in the [MCPTT Client](https://demo.mcopenplatform.org/gitlist/mcop/MCOP-SDK.git/blob/master/docs/Licensing.md) and [Doubango](https://demo.mcopenplatform.org/gitlist/mcop/MCOP-SDK.git/blob/master/docs/Licensing_Doubango.md) files. 

## The MCOP Project


<iframe src="https://player.vimeo.com/video/269823996?title=0" width="640" height="360" frameborder="0" webkitallowfullscreen mozallowfullscreen allowfullscreen></iframe>


## Resources

**MUOAPI** definition, valid for any platform and any programming language:

* [**MUOAPI** Technology neutral definition](https://www.mcopenplatform.org/resources/MUOAPI_definition/)

Documentation:

* [**MCOP Unified Open Application API**](https://www.mcopenplatform.org/resources/MUOAPI/)

<table border='1' cellspacing='0' cellpadding='7'>
<blockquote><tr>
<blockquote><td><b>Features</b></td>
<td><b>Implemented</b></td>
<td><b>Notes</b></td>
</blockquote></tr>
<tr>
<blockquote><td>Private Call</td>
<td align="center"> ✔ </td>
<td> - </td>
</blockquote></tr>
<tr>
<blockquote><td>Prearranged Group Call</td>
<td align="center"> ✔ </td>
<td> - </td>
</blockquote></tr>
<tr>
<blockquote><td>Location</td>
<td align="center"> ✔ </td>
<td> - </td>
</blockquote></tr>
<tr>
<blockquote><td>IDMS</td>
<td align="center"> ✘ </td>
<td> <b>NOTE: Implemented but not included in v0.1 in order to be tested during 2nd MCPTT Plugtest. Will be upgraded after the event.</b> A URL with parameters is provided, and a 3er party authentication is needed to provide a response URL. An example implementation can be found in MCOP Client </td>
</blockquote></tr>
<tr>
<blockquote><td>CMS</td>
<td align="center"> ✘ </td>
<td> <b>NOTE: Implemented but not included in v0.1 in order to be tested during 2nd MCPTT Plugtest. Will be upgraded after the event.</b> http only </td>
</blockquote></tr>
<tr>
<blockquote><td>eMBMS</td>
<td align="center"> ✔ </td>
<td> Available if eMBMS plugin available in the device </td>
</blockquote></tr>
<tr>
<blockquote><td>Affiliation</td>
<td align="center"> ✔ </td>
<td> - </td>
</blockquote></tr>
<tr>
<blockquote><td>SIM Authentication</td>
<td align="center"> ✔ </td>
<td> Available trough plugins </td>
</blockquote></tr>
</blockquote><blockquote></table>
</br>



# org.globalqss.idempiere.LCO.firstname
- Copyright: 2026 https://www.casadelsoftware.com
- Repository: https://bitbucket.org/cdsoftware/globalqss-idempiere-lco.git
- License: GPL 2

## Description
The `globalqss-idempiere-lco` plugin is a custom extension for iDempiere. It extends standard system capabilities by providing database models, and Application Dictionary configurations (2Pack) to support customized business workflows.

## Contributors
- 2026 Casa del Software <info@casadelsoftware.com>

## Components
- iDempiere Plugin [org.globalqss.idempiere.LCO.firstname](org.globalqss.idempiere.LCO.firstname)

## Prerequisites
- Java 11, commands `java` and `javac`.
- iDempiere 10

## Features/Documentation
### Source Structure
```
├── org/
        ├── globalqss/
            ├── util/
                ├── LCO_Utils.java
            ├── model/
                ├── LCO_Callouts.java
                ├── LCO_ValidatorDN.java
```




### Generated Models

| Model | Table | Functional role |
| --- | --- | --- |
| `LCO_Callouts` | `LCO_Callouts` | This file is part of iDempiere ERP Open Source * http://www.idempiere.org * * Copyright (C) Contributors * * This program is free software; you can redistribute it and/or * modify it under the terms of the GNU General Public License * as published by the Free Software Foundation; either version 2 * of the License, or (at your option) any later version. * * This program is distributed in the hope that it will be useful, * but WITHOUT ANY WARRANTY; without even the implied warranty of * MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE. See the * GNU General Public License for more details. * * You should have received a copy of the GNU General Public License * along with this program; if not, write to the Free Software * Foundation, Inc., 51 Franklin Street, Fifth Floor, Boston, * MA 02110-1301, USA. * * Contributors: * - Carlos Ruiz - globalqss * / package org.globalqss.model; import java.util.Properties; import org.adempiere.base.IColumnCallout; import org.adempiere.base.IColumnCalloutFactory; import org.compiere.model.GridField; import org.compiere.model.GridTab; import org.compiere.model.I_C_BPartner; import org.compiere.model.MBPartner; import org.compiere.model.MSysConfig; import org.compiere.util.CLogger; import org.compiere.util.Env; import org.globalqss.util.LCO_Utils; /** User Callout for LCO Localization Colombia @author Carlos Ruiz @version $Id: LCO_Callouts.java,v 1.0 2008/05/26 |
| `LCO_ValidatorDN` | `LCO_ValidatorDN` | This file is part of iDempiere ERP Open Source * http://www.idempiere.org * * Copyright (C) Contributors * * This program is free software; you can redistribute it and/or * modify it under the terms of the GNU General Public License * as published by the Free Software Foundation; either version 2 * of the License, or (at your option) any later version. * * This program is distributed in the hope that it will be useful, * but WITHOUT ANY WARRANTY; without even the implied warranty of * MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE. See the * GNU General Public License for more details. * * You should have received a copy of the GNU General Public License * along with this program; if not, write to the Free Software * Foundation, Inc., 51 Franklin Street, Fifth Floor, Boston, * MA 02110-1301, USA. * * Contributors: * - Carlos Ruiz - globalqss * / package org.globalqss.model; import org.adempiere.base.event.AbstractEventHandler; import org.adempiere.base.event.IEventManager; import org.adempiere.base.event.IEventTopics; import org.adempiere.base.event.LoginEventData; import org.compiere.model.MBPartner; import org.compiere.model.MSysConfig; import org.compiere.model.PO; import org.compiere.util.CLogger; import org.compiere.util.Env; import org.compiere.util.Msg; import org.compiere.util.Util; import org.globalqss.util.LCO_Utils; import org.osgi.service.event.Event; /** Validator or Localization Colombia (First Name - this is a subset of Detailed Names) @author Carlos Ruiz - globalqss - Quality Systems & Solutions - http://globalqss.com |


### Application Dictionary Metadata (2Pack)

| Package / File Name | Purpose & Dictionary Configurations |
| --- | --- |
| `2Pack_2.1.0.zip` | Metadata package containing Application Dictionary (AD) configurations. |
| `2Pack_2.1.1.zip` | Metadata package containing Application Dictionary (AD) configurations. |
| `2Pack_2.1.2.zip` | Metadata package containing Application Dictionary (AD) configurations. |
| `2Pack_2.2.0.zip` | Metadata package containing Application Dictionary (AD) configurations. |
| `2Pack_3.1.1.zip` | Metadata package containing Application Dictionary (AD) configurations. |
| `2Pack_4.1.1.zip` | Metadata package containing Application Dictionary (AD) configurations. |
| `2Pack_4.1.2.zip` | Metadata package containing Application Dictionary (AD) configurations. |
| `2Pack_6.2.0.zip` | Metadata package containing Application Dictionary (AD) configurations. |
| `2Pack_6.2.1.zip` | Metadata package containing Application Dictionary (AD) configurations. |
| `2Pack_8.2.0.zip` | Metadata package containing Application Dictionary (AD) configurations. |
| `AD_BroadcastMessage_Trl_es_CO.xml` | Metadata package containing Application Dictionary (AD) configurations. |
| `AD_Chart_Trl_es_CO.xml` | Metadata package containing Application Dictionary (AD) configurations. |
| `AD_Color_Trl_es_CO.xml` | Metadata package containing Application Dictionary (AD) configurations. |
| `AD_CtxHelpMsg_Trl_es_CO.xml` | Metadata package containing Application Dictionary (AD) configurations. |
| `AD_Element_Trl_es_CO.xml` | Metadata package containing Application Dictionary (AD) configurations. |
| `AD_FieldGroup_Trl_es_CO.xml` | Metadata package containing Application Dictionary (AD) configurations. |
| `AD_Field_Trl_es_CO.xml` | Metadata package containing Application Dictionary (AD) configurations. |
| `AD_Form_Trl_es_CO.xml` | Metadata package containing Application Dictionary (AD) configurations. |
| `AD_InfoColumn_Trl_es_CO.xml` | Metadata package containing Application Dictionary (AD) configurations. |
| `AD_InfoWindow_Trl_es_CO.xml` | Metadata package containing Application Dictionary (AD) configurations. |
| `AD_Menu_Trl_es_CO.xml` | Metadata package containing Application Dictionary (AD) configurations. |
| `AD_Message_Trl_es_CO.xml` | Metadata package containing Application Dictionary (AD) configurations. |
| `AD_PrintColor_Trl_es_CO.xml` | Metadata package containing Application Dictionary (AD) configurations. |
| `AD_PrintFormatItem_Trl_es_CO.xml` | Metadata package containing Application Dictionary (AD) configurations. |
| `AD_PrintFormat_Trl_es_CO.xml` | Metadata package containing Application Dictionary (AD) configurations. |
| `AD_PrintLabelLine_Trl_es_CO.xml` | Metadata package containing Application Dictionary (AD) configurations. |
| `AD_Process_Para_Trl_es_CO.xml` | Metadata package containing Application Dictionary (AD) configurations. |
| `AD_Process_Trl_es_CO.xml` | Metadata package containing Application Dictionary (AD) configurations. |
| `AD_Ref_List_Trl_es_CO.xml` | Metadata package containing Application Dictionary (AD) configurations. |
| `AD_Reference_Trl_es_CO.xml` | Metadata package containing Application Dictionary (AD) configurations. |
| `AD_Tab_Trl_es_CO.xml` | Metadata package containing Application Dictionary (AD) configurations. |
| `AD_Table_Trl_es_CO.xml` | Metadata package containing Application Dictionary (AD) configurations. |
| `AD_Task_Trl_es_CO.xml` | Metadata package containing Application Dictionary (AD) configurations. |
| `AD_WF_Node_Trl_es_CO.xml` | Metadata package containing Application Dictionary (AD) configurations. |
| `AD_Window_Trl_es_CO.xml` | Metadata package containing Application Dictionary (AD) configurations. |
| `AD_Workflow_Trl_es_CO.xml` | Metadata package containing Application Dictionary (AD) configurations. |
| `A_Asset_Group_Trl_es_CO.xml` | Metadata package containing Application Dictionary (AD) configurations. |
| `C_Activity_Trl_es_CO.xml` | Metadata package containing Application Dictionary (AD) configurations. |
| `C_Campaign_Trl_es_CO.xml` | Metadata package containing Application Dictionary (AD) configurations. |
| `C_Charge_Trl_es_CO.xml` | Metadata package containing Application Dictionary (AD) configurations. |
| `C_CountryGroup_Trl_es_CO.xml` | Metadata package containing Application Dictionary (AD) configurations. |
| `C_Country_Trl_es_CO.xml` | Metadata package containing Application Dictionary (AD) configurations. |
| `C_Currency_Trl_es_CO.xml` | Metadata package containing Application Dictionary (AD) configurations. |
| `C_DocType_Trl_es_CO.xml` | Metadata package containing Application Dictionary (AD) configurations. |
| `C_DunningLevel_Trl_es_CO.xml` | Metadata package containing Application Dictionary (AD) configurations. |
| `C_ElementValue_Trl_es_CO.xml` | Metadata package containing Application Dictionary (AD) configurations. |
| `C_Greeting_Trl_es_CO.xml` | Metadata package containing Application Dictionary (AD) configurations. |
| `C_PaymentTerm_Trl_es_CO.xml` | Metadata package containing Application Dictionary (AD) configurations. |
| `C_Region_Trl_es_CO.xml` | Metadata package containing Application Dictionary (AD) configurations. |
| `C_SalesRegion_Trl_es_CO.xml` | Metadata package containing Application Dictionary (AD) configurations. |
| `C_SalesStage_Trl_es_CO.xml` | Metadata package containing Application Dictionary (AD) configurations. |
| `C_TaxCategory_Trl_es_CO.xml` | Metadata package containing Application Dictionary (AD) configurations. |
| `C_Tax_Trl_es_CO.xml` | Metadata package containing Application Dictionary (AD) configurations. |
| `C_UOM_Trl_es_CO.xml` | Metadata package containing Application Dictionary (AD) configurations. |
| `FestivosColombia.zip` | Metadata package containing Application Dictionary (AD) configurations. |
| `GL_Category_Trl_es_CO.xml` | Metadata package containing Application Dictionary (AD) configurations. |
| `GeografiaColombiaCapitales.zip` | Metadata package containing Application Dictionary (AD) configurations. |
| `GeografiaColombiaCompleta.zip` | Metadata package containing Application Dictionary (AD) configurations. |
| `GlobalQSS_FestivosColombiaDoc.xml` | Metadata package containing Application Dictionary (AD) configurations. |
| `GlobalQSS_GeografiaColombiaCapitalesDoc.xml` | Metadata package containing Application Dictionary (AD) configurations. |
| `GlobalQSS_GeografiaColombiaCompletaDoc.xml` | Metadata package containing Application Dictionary (AD) configurations. |
| `LCO_MediosMagneticosBaseData.zip` | Metadata package containing Application Dictionary (AD) configurations. |
| `LCO_MediosMagneticosBaseDataDoc.xml` | Metadata package containing Application Dictionary (AD) configurations. |
| `LCO_RetencionesBaseData.zip` | Metadata package containing Application Dictionary (AD) configurations. |
| `LCO_RetencionesBaseDataDoc.xml` | Metadata package containing Application Dictionary (AD) configurations. |
| `M_PriceList_Trl_es_CO.xml` | Metadata package containing Application Dictionary (AD) configurations. |
| `M_PriceList_Version_Trl_es_CO.xml` | Metadata package containing Application Dictionary (AD) configurations. |
| `M_Product_Category_Trl_es_CO.xml` | Metadata package containing Application Dictionary (AD) configurations. |
| `M_Product_Trl_es_CO.xml` | Metadata package containing Application Dictionary (AD) configurations. |
| `PA_DashboardContent_Trl_es_CO.xml` | Metadata package containing Application Dictionary (AD) configurations. |
| `PA_DocumentStatus_Trl_es_CO.xml` | Metadata package containing Application Dictionary (AD) configurations. |
| `PA_ReportColumn_Trl_es_CO.xml` | Metadata package containing Application Dictionary (AD) configurations. |
| `PA_ReportLine_Trl_es_CO.xml` | Metadata package containing Application Dictionary (AD) configurations. |
| `PP_Order_BOMLine_Trl_es_CO.xml` | Metadata package containing Application Dictionary (AD) configurations. |
| `PP_Order_BOM_Trl_es_CO.xml` | Metadata package containing Application Dictionary (AD) configurations. |
| `PP_Order_Node_Trl_es_CO.xml` | Metadata package containing Application Dictionary (AD) configurations. |
| `PP_Order_Workflow_Trl_es_CO.xml` | Metadata package containing Application Dictionary (AD) configurations. |
| `PP_Product_BOMLine_Trl_es_CO.xml` | Metadata package containing Application Dictionary (AD) configurations. |
| `PP_Product_BOM_Trl_es_CO.xml` | Metadata package containing Application Dictionary (AD) configurations. |
| `PackOut.xml` | Metadata package containing Application Dictionary (AD) configurations. |
| `R_MailText_Trl_es_CO.xml` | Metadata package containing Application Dictionary (AD) configurations. |
| `W_MailMsg_Trl_es_CO.xml` | Metadata package containing Application Dictionary (AD) configurations. |
| `W_Store_Trl_es_CO.xml` | Metadata package containing Application Dictionary (AD) configurations. |
| `category.xml` | Metadata package containing Application Dictionary (AD) configurations. |
| `feature.xml` | Metadata package containing Application Dictionary (AD) configurations. |
| `lco_calloutfactorydn.xml` | Metadata package containing Application Dictionary (AD) configurations. |
| `lco_calloutfactorydnc.xml` | Metadata package containing Application Dictionary (AD) configurations. |
| `lco_calloutfactorywh.xml` | Metadata package containing Application Dictionary (AD) configurations. |
| `lco_modelfactory_inc.xml` | Metadata package containing Application Dictionary (AD) configurations. |
| `lco_modelfactorydn.xml` | Metadata package containing Application Dictionary (AD) configurations. |
| `lco_modelfactorymm.xml` | Metadata package containing Application Dictionary (AD) configurations. |
| `lco_modelfactorywh.xml` | Metadata package containing Application Dictionary (AD) configurations. |
| `lco_modelvalidator_inc.xml` | Metadata package containing Application Dictionary (AD) configurations. |
| `lco_processfactorymm.xml` | Metadata package containing Application Dictionary (AD) configurations. |
| `lco_processfactorywh.xml` | Metadata package containing Application Dictionary (AD) configurations. |
| `lco_validatordn.xml` | Metadata package containing Application Dictionary (AD) configurations. |
| `lco_validatordnc.xml` | Metadata package containing Application Dictionary (AD) configurations. |
| `lco_validatormm.xml` | Metadata package containing Application Dictionary (AD) configurations. |
| `lco_validatorwh.xml` | Metadata package containing Application Dictionary (AD) configurations. |
| `taxidtype_CO.xml` | Metadata package containing Application Dictionary (AD) configurations. |
| `taxidtype_EC.xml` | Metadata package containing Application Dictionary (AD) configurations. |


## Instructions
1. Deploy the `org.globalqss.idempiere.LCO.firstname` OSGi bundle in your iDempiere environment.
2. Restart iDempiere and refresh OSGi bundles to register factories.
3. Configure dictionary and role access rules as needed.

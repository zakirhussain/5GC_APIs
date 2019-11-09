# OpenAPI Specification Files for 3GPP 5G Core Network (Release 16)

[![Build Status](https://travis-ci.org/jdegre/5GC_APIs.svg?branch=master)](https://travis-ci.org/jdegre/5GC_APIs)

The files in this repository have been created by 3GPP, and the master source can be found in the [3GPP site](http://www.3gpp.org/DynaReport/23-series.htm), as part of the official 3GPP Technical Specifications.
```
© 2019, 3GPP Organizational Partners (ARIB, ATIS, CCSA, ETSI, TSDSI, TTA, TTC).
All rights reserved.
```
API version: **September 2019**<br/>
Release status: **Open** <sup>&#x2705;</sup><br/>
Other releases: [Rel-15 (Frozen)](https://github.com/zakirhussain/5gc_apis/tree/Rel-15)<br/>
- [Info about 3GPP Releases and their status](https://www.3gpp.org/specifications/67-releases)
<br/><br/>

## Tools
* [API Parser/Validator and Linter](https://zakirhussain.github.io/parser.html) 
* [Data Type Finder](https://zakirhussain.github.io/types.html)
<br/><br/>

The links below will open the Swagger Editor (v3.6.23) and auto-load the OpenAPI YAML file of each Network Function (NF) API:
<br/>

<!-- APIs -->
## NRF (NF Repository Function)
* [NF Management](https://editor.swagger.io/?url=https://raw.githubusercontent.com/zakirhussain/5gc_apis/master/TS29510_Nnrf_NFManagement.yaml)
* [NF Discovery](https://zakirhussain.github.io/5gc_apis/loader.html?yaml=TS29510_Nnrf_NFDiscovery.yaml)
* [Access Token (OAuth2)](https://zakirhussain.github.io/5gc_apis/loader.html?yaml=TS29510_Nnrf_AccessToken.yaml)
## LMF (Location Management Function)
* [Location](https://zakirhussain.github.io/5gc_apis/loader.html?yaml=TS29572_Nlmf_Location.yaml)
## AMF (Access and Mobility Management Function)
* [Communication](https://zakirhussain.github.io/5gc_apis/loader.html?yaml=TS29518_Namf_Communication.yaml)
* [Event Exposure](https://zakirhussain.github.io/5gc_apis/loader.html?yaml=TS29518_Namf_EventExposure.yaml)
* [Location](https://zakirhussain.github.io/5gc_apis/loader.html?yaml=TS29518_Namf_Location.yaml)
* [MT](https://zakirhussain.github.io/5gc_apis/loader.html?yaml=TS29518_Namf_MT.yaml)
## SMF (Session Management Function)
* [PDU Session](https://zakirhussain.github.io/5gc_apis/loader.html?yaml=TS29502_Nsmf_PDUSession.yaml)
* [Event Exposure](https://zakirhussain.github.io/5gc_apis/loader.html?yaml=TS29508_Nsmf_EventExposure.yaml)
## UDM (Unified Data Management)
* [Subscriber Data Management](https://zakirhussain.github.io/5gc_apis/loader.html?yaml=TS29503_Nudm_SDM.yaml)
* [UE Context Management](https://zakirhussain.github.io/5gc_apis/loader.html?yaml=TS29503_Nudm_UECM.yaml)
* [UE Authentication](https://zakirhussain.github.io/5gc_apis/loader.html?yaml=TS29503_Nudm_UEAU.yaml)
* [Event Exposure](https://zakirhussain.github.io/5gc_apis/loader.html?yaml=TS29503_Nudm_EE.yaml)
* [Parameter Provisioning](https://zakirhussain.github.io/5gc_apis/loader.html?yaml=TS29503_Nudm_PP.yaml)
* [NIDD Authorization](https://zakirhussain.github.io/5gc_apis/loader.html?yaml=TS29503_Nudm_NIDDAU.yaml)
## UDR (Unified Data Repository)
* [Data Repository](https://zakirhussain.github.io/5gc_apis/loader.html?yaml=TS29504_Nudr_DataRepository.yaml)
  * [Subscription Data](https://zakirhussain.github.io/5gc_apis/loader.html?yaml=TS29505_Subscription_Data.yaml)
  * [Policy Data](https://zakirhussain.github.io/5gc_apis/loader.html?yaml=TS29519_Policy_Data.yaml)
  * [Exposure Data](https://zakirhussain.github.io/5gc_apis/loader.html?yaml=TS29519_Exposure_Data.yaml)
  * [Application Data](https://zakirhussain.github.io/5gc_apis/loader.html?yaml=TS29519_Application_Data.yaml)
## AUSF (Authentication Server Function)
* [UE Authentication](https://zakirhussain.github.io/5gc_apis/loader.html?yaml=TS29509_Nausf_UEAuthentication.yaml)
* [SoR (Steering of Roaming) Protection](https://zakirhussain.github.io/5gc_apis/loader.html?yaml=TS29509_Nausf_SoRProtection.yaml)
* [UPU (UE Parameter Update) Protection](https://zakirhussain.github.io/5gc_apis/loader.html?yaml=TS29509_Nausf_UPUProtection.yaml)
## NSSF (Network Slice Selection Function)
* [NSSAI Availability](https://zakirhussain.github.io/5gc_apis/loader.html?yaml=TS29531_Nnssf_NSSAIAvailability.yaml)
* [NS Selection](https://zakirhussain.github.io/5gc_apis/loader.html?yaml=TS29531_Nnssf_NSSelection.yaml)
## SMSF (SMS Function)
* [SM Service](https://zakirhussain.github.io/5gc_apis/loader.html?yaml=TS29540_Nsmsf_SMService.yaml)
## 5G-EIR (5G Equipment Identity Register)
* [Equipment Identity Check](https://zakirhussain.github.io/5gc_apis/loader.html?yaml=TS29511_N5g-eir_EquipmentIdentityCheck.yaml)
## NEF (Network Exposure Function)
* [Packet Flow Description (PFD) Management](https://zakirhussain.github.io/5gc_apis/loader.html?yaml=TS29551_Nnef_PFDmanagement.yaml)
## PCF (Policy Control Function)
* [Policy Authorization](https://zakirhussain.github.io/5gc_apis/loader.html?yaml=TS29514_Npcf_PolicyAuthorization.yaml)
* [Access and Mobility (AM) Policy Control](https://zakirhussain.github.io/5gc_apis/loader.html?yaml=TS29507_Npcf_AMPolicyControl.yaml)
* [Session Management (SM) Policy Control](https://zakirhussain.github.io/5gc_apis/loader.html?yaml=TS29512_Npcf_SMPolicyControl.yaml)
* [Background Data Transfer (BDT) Policy Control](https://zakirhussain.github.io/5gc_apis/loader.html?yaml=TS29554_Npcf_BDTPolicyControl.yaml)
* [Policy Control Event Exposure](https://zakirhussain.github.io/5gc_apis/loader.html?yaml=TS29523_Npcf_EventExposure.yaml)
* [UE Policy Control](https://zakirhussain.github.io/5gc_apis/loader.html?yaml=TS29525_Npcf_UEPolicyControl.yaml)
## BSF (Binding Support Function)
* [Management](https://zakirhussain.github.io/5gc_apis/loader.html?yaml=TS29521_Nbsf_Management.yaml)
## NWDAF (Network Data Analytics Function)
* [Events Subscription](https://zakirhussain.github.io/5gc_apis/loader.html?yaml=TS29520_Nnwdaf_EventsSubscription.yaml)
* [Analytics Info](https://zakirhussain.github.io/5gc_apis/loader.html?yaml=TS29520_Nnwdaf_AnalyticsInfo.yaml)
## HSS (Home Subscriber Server)
* [UE Authentication](https://zakirhussain.github.io/5gc_apis/loader.html?yaml=TS29563_Nhss_UEAU.yaml)
## AF (Application Function)
* [Event Exposure](https://zakirhussain.github.io/5gc_apis/loader.html?yaml=TS29517_Naf_EventExposure.yaml)
## CHF (Charging Function)
* [Spending Limit Control](https://zakirhussain.github.io/5gc_apis/loader.html?yaml=TS29594_Nchf_SpendingLimitControl.yaml)
* [Converged Charging](https://zakirhussain.github.io/5gc_apis/loader.html?yaml=TS32291_Nchf_ConvergedCharging.yaml)
## Common Data Types
* [Common Data](https://zakirhussain.github.io/5gc_apis/loader.html?yaml=TS29571_CommonData.yaml)
## SEPP N32 APIs
* [Handshake (N32-c)](https://zakirhussain.github.io/5gc_apis/loader.html?yaml=TS29573_N32_Handshake.yaml)
* [Forwarding (N32-f)](https://zakirhussain.github.io/5gc_apis/loader.html?yaml=TS29573_JOSEProtectedMessageForwarding.yaml)
* [Telescopic FQDN Mapping](https://zakirhussain.github.io/5gc_apis/loader.html?yaml=TS29573_SeppTelescopicFqdnMapping.yaml)

# Northbound APIs

## Common API Framework (CAPIF)
* [Discover Service](https://zakirhussain.github.io/5gc_apis/loader.html?yaml=TS29222_CAPIF_Discover_Service_API.yaml)
* [Publish Service](https://zakirhussain.github.io/5gc_apis/loader.html?yaml=TS29222_CAPIF_Publish_Service_API.yaml)
* [Events](https://zakirhussain.github.io/5gc_apis/loader.html?yaml=TS29222_CAPIF_Events_API.yaml)
* [API Invoker Management](https://zakirhussain.github.io/5gc_apis/loader.html?yaml=TS29222_CAPIF_API_Invoker_Management_API.yaml)
* [Security](https://zakirhussain.github.io/5gc_apis/loader.html?yaml=TS29222_CAPIF_Security_API.yaml)
* [Access Control Policy](https://zakirhussain.github.io/5gc_apis/loader.html?yaml=TS29222_CAPIF_Access_Control_Policy_API.yaml)
* [Logging API Invocation](https://zakirhussain.github.io/5gc_apis/loader.html?yaml=TS29222_CAPIF_Logging_API_Invocation_API.yaml)
* [Auditing](https://zakirhussain.github.io/5gc_apis/loader.html?yaml=TS29222_CAPIF_Auditing_API.yaml)
* [AEF Authentication](https://zakirhussain.github.io/5gc_apis/loader.html?yaml=TS29222_AEF_Security_API.yaml)

## NEF (Network Exposure Function)
* [Traffic Influence](https://zakirhussain.github.io/5gc_apis/loader.html?yaml=TS29522_TrafficInfluence.yaml)
* [NIDD Configuration Trigger](https://zakirhussain.github.io/5gc_apis/loader.html?yaml=TS29522_NIDDConfigurationTrigger.yaml)
* [Applying BDT Policy](https://zakirhussain.github.io/5gc_apis/loader.html?yaml=TS29522_ApplyingBdtPolicy.yaml)

## SCEF (Service Capability Exposure Function)
NOTE: These APIs are not part of the 5G Core Network; these APIs are exposed by the 4G SCEF to the SCS/AS
* [Event Monitoring](https://zakirhussain.github.io/5gc_apis/loader.html?yaml=TS29122_MonitoringEvent.yaml)
* [Resource Management of Background Data Transfer (BDT)](https://zakirhussain.github.io/5gc_apis/loader.html?yaml=TS29122_ResourceManagementOfBdt.yaml)
* [Chargeable Party](https://zakirhussain.github.io/5gc_apis/loader.html?yaml=TS29122_ChargeableParty.yaml)
* [Non-IP Data Delivery (NIDD)](https://zakirhussain.github.io/5gc_apis/loader.html?yaml=TS29122_NIDD.yaml)
* [Device Triggering](https://zakirhussain.github.io/5gc_apis/loader.html?yaml=TS29122_DeviceTriggering.yaml)
* [Group Message Delivery via MBMS by MB2](https://zakirhussain.github.io/5gc_apis/loader.html?yaml=TS29122_GMDviaMBMSbyMB2.yaml)
* [Group Message Delivery via MBMS by xMB](https://zakirhussain.github.io/5gc_apis/loader.html?yaml=TS29122_GMDviaMBMSbyxMB.yaml)
* [Network Status Reporting](https://zakirhussain.github.io/5gc_apis/loader.html?yaml=TS29122_ReportingNetworkStatus.yaml)
* [Communication Patterns (CP) Parameters Provisioning](https://zakirhussain.github.io/5gc_apis/loader.html?yaml=TS29122_CpProvisioning.yaml)
* [Packet Flow Description (PFD) Management](https://zakirhussain.github.io/5gc_apis/loader.html?yaml=TS29122_PfdManagement.yaml)
* [Enhanced Coverage Restriction Control](https://zakirhussain.github.io/5gc_apis/loader.html?yaml=TS29122_ECRControl.yaml)
* [Network Parameter Configuration](https://zakirhussain.github.io/5gc_apis/loader.html?yaml=TS29122_NpConfiguration.yaml)
* [Application Server (AS) Session with QoS](https://zakirhussain.github.io/5gc_apis/loader.html?yaml=TS29122_AsSessionWithQoS.yaml)
* [MSISDN-less Mobile-Originated SMS](https://zakirhussain.github.io/5gc_apis/loader.html?yaml=TS29122_MsisdnLessMoSms.yaml)
* [Common Data](https://zakirhussain.github.io/5gc_apis/loader.html?yaml=TS29122_CommonData.yaml)

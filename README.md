# Pre-requisites:
* Person Account is enabled
* Multi-currency is enabled and setup
* Person Account Duplication rules are disabled

# Post-Deployment Steps:
* Assing CRUD persmissions to the required profiles
* Change default homepage for Sales App
* Assign relevant FLS to required profiles
* Assign page layouts to the required profiles


## Metadata Changes
Flows
* Partner_Staging_After_Insert
* SubscribedProduct_Before_Insert_Update
* Create_Subscription

CustomObjects
* Subscription__c
* PartnerStaging__c
* SubscribedProduct__c

CustomFields
* PartnerStaging__c.AddressLine1__c
* PartnerStaging__c.AddressLine2__c
* PartnerStaging__c.AddressLine3__c
* PartnerStaging__c.Country__c
* PartnerStaging__c.CountyState__c
* PartnerStaging__c.CustomerFirstName__c
* PartnerStaging__c.CustomerLastName__c
* PartnerStaging__c.PostCode__c
* PartnerStaging__c.Processed__c
* PartnerStaging__c.ProcessingErrorDetails__c
* PartnerStaging__c.Subscription_Currency__c
* PartnerStaging__c.SubscriptionTier__c
* PartnerStaging__c.SubscriptionType__c
* PartnerStaging__c.SubscriptionValue__c
* Subscription__c.Account__c
* Subscription__c.Active__c
* Subscription__c.Description__c
* Subscription__c.Subscription_Tier__c
* Subscription__c.Subscription_Type__c
* Subscription__c.Value__c
* SubscribedProduct__c.Product__c
* SubscribedProduct__c.Subscription__c
* SubscribedProduct__c.UniqueKey__c


PageLayouts
* PartnerStaging__c-Partner Staging Layout
* PersonAccount-Person Account Layout
* Subscription__c-Subscription Layout
* SubscribedProduct__c-SubscribedProduct Layout

CustomTabs
* Subscription__c
* PartnerStaging__c
* SubscribedProduct__c

QuickActions
* Product.Create_Subscription
* Account.Create_Subscription

FlexiPages
* Home_Page_Default1

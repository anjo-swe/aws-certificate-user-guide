# AWS Certificate Manager User Guide

-----
*****Copyright &copy; 2020 Amazon Web Services, Inc. and/or its affiliates. All rights reserved.*****

-----
Amazon's trademarks and trade dress may not be used in 
     connection with any product or service that is not Amazon's, 
     in any manner that is likely to cause confusion among customers, 
     or in any manner that disparages or discredits Amazon. All other 
     trademarks not owned by Amazon are the property of their respective
     owners, who may or may not be affiliated with, connected to, or 
     sponsored by Amazon.

-----
## Contents
+ [What Is AWS Certificate Manager?](acm-overview.md)
   + [Concepts](acm-concepts.md)
   + [ACM Certificate Characteristics](acm-certificate.md)
   + [Supported Regions](acm-regions.md)
   + [Services Integrated with AWS Certificate Manager](acm-services.md)
   + [Site Seals and Trust Logos](acm-siteseal.md)
   + [Quotas](acm-limits.md)
   + [Best Practices](acm-bestpractices.md)
   + [Pricing for AWS Certificate Manager](acm-billing.md)
+ [Security in AWS Certificate Manager](security.md)
   + [Data Protection in AWS Certificate Manager](data-protection.md)
   + [Identity and Access Management for AWS Certificate Manager](security-iam.md)
      + [Overview of Managing Access to Your ACM Resources](authen-overview.md)
      + [AWS Managed Policies](authen-awsmanagedpolicies.md)
      + [Customer Managed Policies](authen-custmanagedpolicies.md)
      + [Inline Policies](authen-inlinepolicies.md)
      + [ACM API Permissions: Actions and Resources Reference](authen-apipermissions.md)
   + [Logging and Monitoring for AWS Certificate Manager](security-logging-and-monitoring.md)
      + [Using CloudTrail with AWS Certificate Manager](cloudtrail.md)
         + [ACM API Actions Supported in CloudTrail Logging](acm-supported-actions-in-cloudtrail.md)
         + [Logging for ACM-Related API Calls](ct-related.md)
   + [Resilience in AWS Certificate Manager](disaster-recovery-resiliency.md)
   + [Infrastructure Security in AWS Certificate Manager](infrastructure-security.md)
+ [Setting Up](setup.md)
   + [Set Up AWS and IAM](setup-aws-iam.md)
   + [Register a Domain Name](setup-domain.md)
   + [Set Up Your Website or Application](setup-website.md)
   + [(Optional) Configure Email for Your Domain](setup-email.md)
   + [(Optional) Configure a CAA Record](setup-caa.md)
+ [Getting Started](gs.md)
   + [Request a Public Certificate](gs-acm-request-public.md)
   + [Request a Private Certificate](gs-acm-request-private.md)
   + [Export a Private Certificate](gs-acm-export-private.md)
   + [Use DNS to Validate Domain Ownership](gs-acm-validate-dns.md)
   + [Use Email to Validate Domain Ownership](gs-acm-validate-email.md)
   + [List ACM–Managed Certificates](gs-acm-list.md)
   + [Describe ACM Certificates](gs-acm-describe.md)
   + [Delete ACM–Managed Certificates](gs-acm-delete.md)
   + [Install ACM Certificates](gs-acm-install.md)
   + [Resend Validation Email (Optional)](gs-acm-resend.md)
+ [Managed Renewal for ACM's Amazon-Issued Certificates](managed-renewal.md)
   + [How Domain Validation Works](how-domain-validation-works.md)
   + [Check a Certificate's Renewal Status](check-certificate-renewal-status.md)
   + [Request a Domain Validation Email for Certificate Renewal](request-domain-validation-email-for-renewal.md)
+ [Importing Certificates into AWS Certificate Manager](import-certificate.md)
   + [Prerequisites for Importing Certificates](import-certificate-prerequisites.md)
   + [Certificate and Key Format for Importing](import-certificate-format.md)
   + [Import a Certificate](import-certificate-api-cli.md)
   + [Reimport a Certificate](import-reimport.md)
+ [Tagging AWS Certificate Manager Certificates](tags.md)
   + [Tag Restrictions](tags-restrictions.md)
   + [Managing Tags](tags-manage.md)
+ [Using the ACM API](sdk.md)
   + [Adding Tags to a Certificate](sdk-addtag.md)
   + [Deleting a Certificate](sdk-delete.md)
   + [Describing a Certificate](sdk-describe.md)
   + [Exporting a Certificate](sdk-export.md)
   + [Retrieve a Certificate and Certificate Chain](sdk-get.md)
   + [Importing a Certificate](sdk-import.md)
   + [Listing Certificates](sdk-list.md)
   + [Renewing a Certificate](sdk-renew.md)
   + [Listing Certificate Tags](sdk-listtag.md)
   + [Removing Tags from a Certificate](sdk-tagremove.md)
   + [Requesting a Certificate](sdk-request.md)
   + [Resending Validation Email](sdk-validate.md)
+ [Troubleshooting](troubleshooting.md)
   + [Troubleshooting Certificate Requests](troubleshooting-cert-requests.md)
      + [Certificate Request Times Out](troubleshooting-timed-out.md)
      + [Certificate Request Fails](troubleshooting-failed.md)
   + [Troubleshooting Certificate Validation](certificate-validation.md)
      + [Troubleshoot DNS Validation Problems](troubleshooting-DNS-validation.md)
      + [Troubleshoot Email Validation Problems](troubleshooting-email-validation.md)
   + [Troubleshooting Managed Certificate Renewal](troubleshooting-renewal.md)
   + [Troubleshooting Other Problems](misc-problems.md)
      + [Troubleshoot Certificate Import Problems](troubleshoot-import.md)
      + [Troubleshoot Certificate Pinning Problems](troubleshooting-pinning.md)
      + [Troubleshoot API Gateway Problems](troubleshoot-apigateway.md)
   + [Handling Exceptions](exceptions.md)
+ [Document History](dochistory.md)
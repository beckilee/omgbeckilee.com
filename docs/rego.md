# Rego code samples

Rego is a declarative policy-as-code language from the creators of the [Open Policy Agent (OPA)](https://www.openpolicyagent.org/){ target="_blank" rel="noopener noreferrer" } engine. I've written quite a lot of Rego policies to check infrastructure-as-code! Some rules were incorporated into the [Fugue](https://www.fugue.co){ target="_blank" rel="noopener noreferrer" } policy library. I also wrote most of the custom rules in Fugue's [example custom rules](https://github.com/fugue/custom-rules){ target="_blank" rel="noopener noreferrer" } repository. Here is a small selection of policies for use with Fugue:

**Simple custom rules:**

- [AWS S3 buckets must have a `stage=prod` tag](https://github.com/fugue/custom-rules/blob/master/simple/AWS.S3.Bucket_StageProdTags.rego){ target="_blank" rel="noopener noreferrer" }
- [Azure Virtual Machine instances must be assigned to availability sets](https://github.com/fugue/custom-rules/blob/master/simple/Azure.Compute.VirtualMachine_RequireAvailabilitySet.rego){ target="_blank" rel="noopener noreferrer" }
- [Google persistent disks must be between 50 and 100 GB in size](https://github.com/fugue/custom-rules/blob/master/simple/Google.Compute.Disk_Size.rego){ target="_blank" rel="noopener noreferrer" }

**Advanced custom rules:**

- [AWS S3 buckets containing CloudTrail logs must be private](https://github.com/fugue/custom-rules/blob/master/advanced/Advanced_AWS.S3_BucketsCloudTrailLogs.rego){ target="_blank" rel="noopener noreferrer" }
- [Azure managed disks running Linux must have an `application` tag](https://github.com/fugue/custom-rules/blob/master/advanced/Advanced_Azure.Compute.ManagedDisk_LinuxRequireTags.rego){ target="_blank" rel="noopener noreferrer" }
- [Google projects must have a default audit log configuration](https://github.com/fugue/custom-rules/blob/master/advanced/Advanced_Google_DefaultAuditLogConfig.rego){ target="_blank" rel="noopener noreferrer" }

!!! tip
    Interested in learning Rego? Check out my [Rego 101](blog-rego-101.md) blog post series.
# Actions, Resources, and Condition Keys for Amazon SageMaker<a name="list_amazonsagemaker"></a>

Amazon SageMaker \(service prefix: `sagemaker`\) provides the following service\-specific resources, actions, and condition context keys for use in IAM permission policies\.

References:
+ Learn how to [configure this service](https://docs.aws.amazon.com/sagemaker/latest/dg/)\.
+ View a list of the [API operations available for this service](https://docs.aws.amazon.com/sagemaker/latest/dg/)\.
+ Learn how to secure this service and its resources by [using IAM](https://docs.aws.amazon.com/sagemaker/latest/dg/authentication-and-access-control.html) permission policies\.

**Topics**
+ [Actions Defined by Amazon SageMaker](#amazonsagemaker-actions-as-permissions)
+ [Resources Defined by Amazon SageMaker](#amazonsagemaker-resources-for-iam-policies)
+ [Condition Keys for Amazon SageMaker](#amazonsagemaker-policy-keys)

## Actions Defined by Amazon SageMaker<a name="amazonsagemaker-actions-as-permissions"></a>

You can specify the following actions in the `Action` element of an IAM policy statement\. Use policies to grant permissions to perform an operation in AWS\. When you use an action in a policy, you usually allow or deny access to the API operation or CLI command with the same name\. However, in some cases, a single action controls access to more than one operation\. Alternatively, some operations require several different actions\.

The **Resource** column indicates whether each action supports resource\-level permissions\. If there is no value for this column, you must specify all resources \("\*"\) in the `Resource` element of your policy statement\. If the column includes a resource type, then you can specify an ARN of that type in a statement with that action\. Required resources are indicated in the table with an asterisk \(\*\)\. If you specify a resource\-level permission ARN in a statement using this action, then it must be of this type\. Some actions support multiple resource types\. If the resource type is optional \(not indicated as required\), then you can choose to use one but not the other\.

For details about the columns in the following table, see [The Actions Table](reference_policies_actions-resources-contextkeys.md#actions_table)\.


****  
[\[See the AWS documentation website for more details\]](http://docs.aws.amazon.com/IAM/latest/UserGuide/list_amazonsagemaker.html)

## Resources Defined by Amazon SageMaker<a name="amazonsagemaker-resources-for-iam-policies"></a>

The following resource types are defined by this service and can be used in the `Resource` element of IAM permission policy statements\. Each action in the [Actions table](#amazonsagemaker-actions-as-permissions) identifies the resource types that can be specified with that action\. A resource type can also define which condition keys you can include in a policy\. These keys are displayed in the last column of the table\. For details about the columns in the following table, see [The Resource Types Table](reference_policies_actions-resources-contextkeys.md#resources_table)\.


****  

| Resource Types | ARN | Condition Keys | 
| --- | --- | --- | 
|   labeling\-job  |  arn:$\{Partition\}:sagemaker:$\{Region\}:$\{Account\}:labeling\-job/$\{LabelingJobName\}  |   [ aws:ResourceTag/$\{TagKey\} ](#amazonsagemaker-aws_ResourceTag___TagKey_)   [ sagemaker:ResourceTag/$\{TagKey\} ](#amazonsagemaker-sagemaker_ResourceTag___TagKey_)   | 
|   workteam  |  arn:$\{Partition\}:sagemaker:$\{Region\}:$\{Account\}:workteam/$\{WorkteamName\}  |   [ aws:ResourceTag/$\{TagKey\} ](#amazonsagemaker-aws_ResourceTag___TagKey_)   [ sagemaker:ResourceTag/$\{TagKey\} ](#amazonsagemaker-sagemaker_ResourceTag___TagKey_)   | 
|   notebook\-instance  |  arn:$\{Partition\}:sagemaker:$\{Region\}:$\{Account\}:notebook\-instance/$\{NotebookInstanceName\}  |   [ aws:ResourceTag/$\{TagKey\} ](#amazonsagemaker-aws_ResourceTag___TagKey_)   [ sagemaker:ResourceTag/$\{TagKey\} ](#amazonsagemaker-sagemaker_ResourceTag___TagKey_)   | 
|   notebook\-instance\-lifecycle\-config  |  arn:$\{Partition\}:sagemaker:$\{Region\}:$\{Account\}:notebook\-instance\-lifecycle\-config/$\{NotebookInstanceLifecycleConfigName\}  |  | 
|   code\-repository  |  arn:$\{Partition\}:sagemaker:$\{Region\}:$\{Account\}:code\-repository/$\{CodeRepositoryName\}  |  | 
|   algorithm  |  arn:$\{Partition\}:sagemaker:$\{Region\}:$\{Account\}:algorithm/$\{AlgorithmName\}  |  | 
|   training\-job  |  arn:$\{Partition\}:sagemaker:$\{Region\}:$\{Account\}:training\-job/$\{TrainingJobName\}  |   [ aws:ResourceTag/$\{TagKey\} ](#amazonsagemaker-aws_ResourceTag___TagKey_)   [ sagemaker:ResourceTag/$\{TagKey\} ](#amazonsagemaker-sagemaker_ResourceTag___TagKey_)   | 
|   hyper\-parameter\-tuning\-job  |  arn:$\{Partition\}:sagemaker:$\{Region\}:$\{Account\}:hyper\-parameter\-tuning\-job/$\{HyperParameterTuningJobName\}  |   [ aws:ResourceTag/$\{TagKey\} ](#amazonsagemaker-aws_ResourceTag___TagKey_)   [ sagemaker:ResourceTag/$\{TagKey\} ](#amazonsagemaker-sagemaker_ResourceTag___TagKey_)   | 
|   model\-package  |  arn:$\{Partition\}:sagemaker:$\{Region\}:$\{Account\}:model\-package/$\{ModelPackageName\}  |  | 
|   model  |  arn:$\{Partition\}:sagemaker:$\{Region\}:$\{Account\}:model/$\{ModelName\}  |   [ aws:ResourceTag/$\{TagKey\} ](#amazonsagemaker-aws_ResourceTag___TagKey_)   [ sagemaker:ResourceTag/$\{TagKey\} ](#amazonsagemaker-sagemaker_ResourceTag___TagKey_)   | 
|   endpoint\-config  |  arn:$\{Partition\}:sagemaker:$\{Region\}:$\{Account\}:endpoint\-config/$\{EndpointConfigName\}  |   [ aws:ResourceTag/$\{TagKey\} ](#amazonsagemaker-aws_ResourceTag___TagKey_)   [ sagemaker:ResourceTag/$\{TagKey\} ](#amazonsagemaker-sagemaker_ResourceTag___TagKey_)   | 
|   endpoint  |  arn:$\{Partition\}:sagemaker:$\{Region\}:$\{Account\}:endpoint/$\{EndpointName\}  |   [ aws:ResourceTag/$\{TagKey\} ](#amazonsagemaker-aws_ResourceTag___TagKey_)   [ sagemaker:ResourceTag/$\{TagKey\} ](#amazonsagemaker-sagemaker_ResourceTag___TagKey_)   | 
|   transform\-job  |  arn:$\{Partition\}:sagemaker:$\{Region\}:$\{Account\}:transform\-job/$\{TransformJobName\}  |   [ aws:ResourceTag/$\{TagKey\} ](#amazonsagemaker-aws_ResourceTag___TagKey_)   [ sagemaker:ResourceTag/$\{TagKey\} ](#amazonsagemaker-sagemaker_ResourceTag___TagKey_)   | 
|   compilation\-job  |  arn:$\{Partition\}:sagemaker:$\{Region\}:$\{Account\}:compilation\-job/$\{CompilationJobName\}  |  | 

## Condition Keys for Amazon SageMaker<a name="amazonsagemaker-policy-keys"></a>

Amazon SageMaker defines the following condition keys that can be used in the `Condition` element of an IAM policy\. You can use these keys to further refine the conditions under which the policy statement applies\. For details about the columns in the following table, see [The Condition Keys Table](reference_policies_actions-resources-contextkeys.md#context_keys_table)\.

To view the global condition keys that are available to all services, see [Available Global Condition Keys](reference_policies_condition-keys.html#AvailableKeys) in the *IAM Policy Reference*\.


****  

| Condition Keys | Description | Type | 
| --- | --- | --- | 
|   [ aws:RequestTag/$\{TagKey\} ](https://docs.aws.amazon.com/IAM/latest/UserGuide/list_amazonsagemaker.html#amazonsagemaker-policy-keys)  | A key that is present in the request the user makes to the SageMaker service\. | String | 
|   [ aws:ResourceTag/$\{TagKey\} ](https://docs.aws.amazon.com/IAM/latest/UserGuide/list_amazonsagemaker.html#amazonsagemaker-policy-keys)  | A tag key and value pair\. | String | 
|   [ aws:TagKeys ](https://docs.aws.amazon.com/IAM/latest/UserGuide/list_amazonsagemaker.html#amazonsagemaker-policy-keys)  | The list of all the tag key names associated with the resource in the request\. | String | 
|   [ sagemaker:AcceleratorTypes ](https://docs.aws.amazon.com/IAM/latest/UserGuide/list_amazonsagemaker.html#amazonsagemaker-policy-keys)  | The list of all accelerator types associated with the resource in the request\. | ArrayOfString | 
|   [ sagemaker:DirectInternetAccess ](https://docs.aws.amazon.com/IAM/latest/UserGuide/list_amazonsagemaker.html#amazonsagemaker-policy-keys)  | The direct internet access associated with the resource in the request\. | String | 
|   [ sagemaker:FileSystemAccessMode ](https://docs.aws.amazon.com/IAM/latest/UserGuide/list_amazonsagemaker.html#amazonsagemaker-policy-keys)  | File system access mode associated with the resource in the request\. | String | 
|   [ sagemaker:FileSystemDirectoryPath ](https://docs.aws.amazon.com/IAM/latest/UserGuide/list_amazonsagemaker.html#amazonsagemaker-policy-keys)  | File system directory path associated with the resource in the request\. | String | 
|   [ sagemaker:FileSystemId ](https://docs.aws.amazon.com/IAM/latest/UserGuide/list_amazonsagemaker.html#amazonsagemaker-policy-keys)  | A file system ID associated with the resource in the request\. | String | 
|   [ sagemaker:FileSystemType ](https://docs.aws.amazon.com/IAM/latest/UserGuide/list_amazonsagemaker.html#amazonsagemaker-policy-keys)  | File system type associated with the resource in the request\. | String | 
|   [ sagemaker:InstanceTypes ](https://docs.aws.amazon.com/IAM/latest/UserGuide/list_amazonsagemaker.html#amazonsagemaker-policy-keys)  | The list of all instance types associated with the resource in the request\. | ArrayOfString | 
|   [ sagemaker:InterContainerTrafficEncryption ](https://docs.aws.amazon.com/IAM/latest/UserGuide/list_amazonsagemaker.html#amazonsagemaker-policy-keys)  | The inter container traffic encryption associated with the resource in the request\. | Bool | 
|   [ sagemaker:MaxRuntimeInSeconds ](https://docs.aws.amazon.com/IAM/latest/UserGuide/list_amazonsagemaker.html#amazonsagemaker-policy-keys)  | The max runtime in seconds associated with the resource in the request\. | Numeric | 
|   [ sagemaker:ModelArn ](https://docs.aws.amazon.com/IAM/latest/UserGuide/list_amazonsagemaker.html#amazonsagemaker-policy-keys)  | The model arn associated with the resource in the request\. | ARN | 
|   [ sagemaker:NetworkIsolation ](https://docs.aws.amazon.com/IAM/latest/UserGuide/list_amazonsagemaker.html#amazonsagemaker-policy-keys)  | The network isolation associated with the resource in the request\. | Bool | 
|   [ sagemaker:OutputKmsKey ](https://docs.aws.amazon.com/IAM/latest/UserGuide/list_amazonsagemaker.html#amazonsagemaker-policy-keys)  | The output kms key associated with the resource in the request\. | ARN | 
|   [ sagemaker:ResourceTag/ ](https://docs.aws.amazon.com/IAM/latest/UserGuide/list_amazonsagemaker.html#amazonsagemaker-policy-keys)  | The preface string for a tag key and value pair attached to a resource\. | String | 
|   [ sagemaker:ResourceTag/$\{TagKey\} ](https://docs.aws.amazon.com/IAM/latest/UserGuide/list_amazonsagemaker.html#amazonsagemaker-policy-keys)  | A tag key and value pair\. | String | 
|   [ sagemaker:RootAccess ](https://docs.aws.amazon.com/IAM/latest/UserGuide/list_amazonsagemaker.html#amazonsagemaker-policy-keys)  | The root access associated with the resource in the request\. | String | 
|   [ sagemaker:VolumeKmsKey ](https://docs.aws.amazon.com/IAM/latest/UserGuide/list_amazonsagemaker.html#amazonsagemaker-policy-keys)  | The volume kms key associated with the resource in the request\. | ARN | 
|   [ sagemaker:VpcSecurityGroupIds ](https://docs.aws.amazon.com/IAM/latest/UserGuide/list_amazonsagemaker.html#amazonsagemaker-policy-keys)  | The list of all vpc security group ids associated with the resource in the request\. | ArrayOfString | 
|   [ sagemaker:VpcSubnets ](https://docs.aws.amazon.com/IAM/latest/UserGuide/list_amazonsagemaker.html#amazonsagemaker-policy-keys)  | The list of all vpc subnets associated with the resource in the request\. | ArrayOfString | 
|   [ sagemaker:WorkteamArn ](https://docs.aws.amazon.com/IAM/latest/UserGuide/list_amazonsagemaker.html#amazonsagemaker-policy-keys)  | The workteam arn associated to the request\. | ARN | 
|   [ sagemaker:WorkteamType ](https://docs.aws.amazon.com/IAM/latest/UserGuide/list_amazonsagemaker.html#amazonsagemaker-policy-keys)  | The workteam type associated to the request\. This can be public\-crowd, private\-crowd or vendor\-crowd\. | String | 
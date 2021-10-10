---
key: vale
title: Index
author: Dibya
date: 9th Nov 2021
layout: template
---
#### Links to other pages:

- [Indian Airforce](/topics/indian_airforce.md)

- [Indian Army](/topics/indian_airforce.md)

- [Indian Army](/topics/indian_navy.md)

# Reference Pages of IBM:

## Step 5: Manage your invoices and payment methods

Before you start working with resources in your account, familiarize yourself with where you can manage your payment method and access your invoices.

### Managing your payment method

- To manage your payment method for an account that's billed in USD currency, go to **Manage** > **Billing and usage***, and select **Payments**.
- To manage your payment method for an account that's billed in non-USD currency, go to [IBM Billing](https://myibm.ibm.com/billing).
Accessing your invoices

To access an invoice for an account that's billed in USD currency, go to Manage > Billing and usage, and select Invoices.
To access an invoice for an account that's billed in non-USD currency, go to Manage > Billing and usage, and select Invoices. Then, click IBM Invoices.

## Step 7: Create your resource groups

Resource groups provide a way for you to easily manage access to multiple resources and to view billing usage for a set of resources. With your Pay-As-You-Go account, you can create more resource groups in addition to the default resource group that's included when you first created your Lite account.

1. Go to **Manage** > **Account** > **Account resources** > **Resource groups**.
2. Click **Create**.
3. Enter a name for your resource group, and click **Add**.

See [What makes a good resource group strategy?](https://cloud.ibm.com/docs/account?topic=account-account_setup#resource-group-strategy) for details about how to optimally organize resources in your resource groups.

## Step 9: Invite users to your account

You're ready to invite users to your account and grant them access based on the resources they will work with and the tasks they'll perform. If you want users to create resources from the catalog and assign the resources to a resource group, the following access is required:

- Viewer role or higher on the resource group.
- Editor or administrator role on the service.


Complete the following steps:

1. Go to **Manage** > **Access (IAM)** > **Users**.
2. Click **Invite users**.
3. Specify the email address of the user. If you are inviting more than one user, they are all assigned the same access.
4. Add the user to one or more of the access groups that you created in the previous step.
5. Click **Invite**.

To learn more about the invitation flow and how users can accept invitations, see [Inviting users to an account](https://cloud.ibm.com/docs/account?topic=account-iamuserinv&interface=ui).



![Indian Army Logo](https://upload.wikimedia.org/wikipedia/commons/d/dd/A_logo_for_indian_army.png)

#### Checkbox Selected

```
[X] Wake up
[X] Get out of bed
```
[X]  Wake up

[X]  Get out of bed

#### Checkbox Cleared

```
[] Wake up
[] Get out of bed
```
[]  Wake up

[]  Get out of bed


This, `index.md`, is the front matter, Jekyll transformer recognises if the page starts with three `---` and end with three `---` , example:

```
---
author: Dibya
---
```

### This page is written by {{page.author}} on {{page.date}} at {{site.place}} in {{site.when}}

{% for item in site.data.datafile %}
- {{item.year}} : {{item.film}}
{% endfor %}

{% include sample_text.md %}

```
Following is the liquid `syntax` for _data file
```

Lorem Ipsum is simply dummy text of the printing and typesetting industry. Lorem Ipsum has been the industry's standard dummy text ever since the 1500s, when an unknown printer took a galley of type and scrambled it to make a type specimen book. It has survived not only five centuries, but also the leap into electronic typesetting, remaining essentially unchanged. It was popularised in the 1960s with the release of Letraset sheets containing Lorem Ipsum passages, and more recently with desktop publishing software like Aldus PageMaker including versions of Lorem Ipsum.

#### Steps (Ordered List):

You can keep 1, 2, 3, as serial numbers, and just 1,1,1,1,1 will also show as steps

1. Lorem Ipsum is simply dummy text of the printing and typesetting industry. 
2. Lorem Ipsum has been the industry's standard dummy text ever since the 1500s, when an unknown printer took a galley of type and scrambled it to make a type specimen book. It has survived not only five centuries, but also the leap into electronic typesetting, remaining essentially unchanged. 
3. It was popularised in the 1960s with the release of Letraset sheets containing Lorem Ipsum passages, and more recently with desktop publishing software like Aldus PageMaker including versions of Lorem Ipsum.


#### Unordered List 
Listed with -, example:

```
- Example
- Example
- Example
```

- Example
- Example
- Example

#### Table:

```
| column heading |
column heading |
|------------------------|-----
-----------------|
| row text | row text |
| row text | row text |
```

| Name | Type | Description |
| ------ | ---- | ------- |
|Example|Example|Example|
|Example|Example|Example|

#### Code Block:

Code block is enclosed within ```

```
// This is a JS example
var test = "Hello";
console.log(test);
```

### Code inline:

Code inline is enclosed within `

`isEnabled:True`
`CTRL`

#### Link:
This is a [link](https://www.google.com/)

---
title: Amazon
linktitle: Amazon
type: docs
description: Setup Jenkins X on EKS on AWS
date: 2017-02-01
publishdate: 2017-02-01
lastmod: 2020-02-21
weight: 20
aliases:
  - /v3/admin/platform/eks
---

---
**NOTE**

* Ensure you are logged into GitHub else you will get a 404 error when clicking the links below
* ECR repository needs to be created before running the quickstart or importing existing projects.

---

### EKS + Terraform
This is our current recommended quickstart for EKS:

*  <a href="https://github.com/jx3-gitops-repositories/jx3-terraform-eks/generate" target="github" class="btn bg-primary text-light">Create Git Repository</a> based on the [jx3-gitops-repositories/jx3-terraform-eks](https://github.com/jx3-gitops-repositories/jx3-terraform-eks)  
   
    * if the above button does not work then please [Login to GitHub](https://github.com/login) first and then retry the button

* `git clone` the new repository and `cd`  into the git clone

*  <a href="https://github.com/jx3-gitops-repositories/jx3-terraform-eks/blob/master/README.md"
    target="github" class="btn bg-primary text-light" 
    title="use your new git repository to create your cloud infrastructure and install Jenkins X">
    Create your infrastructure
  </a> 

*  <a href="/v3/develop/create-project/" class="btn bg-primary text-light">Create or import projects</a>

# CI Workflow (Pt. 1)

## Pulled gradle.yml from Github workflow
<img width="1440" alt="Pulled gradle yml from Github Workflow" src="https://user-images.githubusercontent.com/53208269/203680492-9c66eeab-ccc8-4712-9928-9cd9ef629c89.png">

## Build with Gradle
<img width="1440" alt="Comment added to gradle yml file" src="https://user-images.githubusercontent.com/53208269/203680629-e73e0334-77a5-4863-b5b1-dfa9eae47d38.png">
<img width="1440" alt="Build with Gradle 1" src="https://user-images.githubusercontent.com/53208269/203680541-04e7849e-a18d-4982-83c1-1cc573c4baf7.png">
<img width="1440" alt="Build with Gradle 2" src="https://user-images.githubusercontent.com/53208269/203680550-643f9da4-b217-4b1a-8160-b8c64fec29a5.png">
<img width="1440" alt="Build with Gradle 3" src="https://user-images.githubusercontent.com/53208269/203680560-9e777136-112a-4d6d-ab7a-1c20bfd59ca2.png">

---

# CD Workflow (Pt. 2)

## Create GKE cluster
<img width="1440" alt="Create cmpe172 cluster" src="https://user-images.githubusercontent.com/53208269/204433945-ce9870b9-aa65-451e-9b40-8ba636602330.png">

## Enable APIs
<img width="1440" alt="API Library" src="https://user-images.githubusercontent.com/53208269/204433997-1144f215-ad78-4aeb-b1da-a7243339dd5e.png">
<img width="1440" alt="Enable access to APIs" src="https://user-images.githubusercontent.com/53208269/204433970-7e7c38fc-6ab9-49a3-8464-7b5fb9c32713.png">

## Find GKE Project ID
<img width="1440" alt="Cloud overview dashboard" src="https://user-images.githubusercontent.com/53208269/204434120-e906e20b-2b2b-4215-adb3-dc5a3f1a8491.png">

## Create Service Account
<img width="1440" alt="Create service account" src="https://user-images.githubusercontent.com/53208269/204434152-eb1d3170-a932-4ba3-9a69-07c47fbeb200.png">
<img width="1440" alt="Service accounts" src="https://user-images.githubusercontent.com/53208269/204434162-9f9fa78d-bca2-4fb6-ad13-fe226e37b3ab.png">

## Grant Permissions
<img width="1440" alt="Permissions being added to cmpe172" src="https://user-images.githubusercontent.com/53208269/204434218-16f78177-c5cb-442f-89d6-5fd4ad2062c3.png">
<img width="1440" alt="Kubernetes Engine Developer and Storage admin permissions added" src="https://user-images.githubusercontent.com/53208269/204434229-3abc1a35-920c-42d1-a666-196bff6e587b.png">

## Create New Private Key
<img width="1440" alt="Create new key for spring-gumball" src="https://user-images.githubusercontent.com/53208269/204434404-ff436210-bbcf-4556-8b2e-513b6544c68f.png">
<img width="1440" alt="private JSON key being created for spring-gumball" src="https://user-images.githubusercontent.com/53208269/204434409-a935560e-6f18-49ec-88b1-b6e00eb7d958.png">
<img width="1440" alt="key created for spring-gumball" src="https://user-images.githubusercontent.com/53208269/204434427-3ae92709-feef-47cd-a917-b8a449cdc019.png">

## GKE_PROJECT and GKE_SA_KEY secrets created
<img width="1440" alt="GKE_PROJECT secret created 1" src="https://user-images.githubusercontent.com/53208269/204434505-9cc08f03-b7ef-4c96-9aa0-ce613fb82fd6.png">
<img width="1440" alt="GKE_PROJECT secret created 2" src="https://user-images.githubusercontent.com/53208269/204434510-60e8afc3-50df-4165-876d-188aa20517a0.png">
<img width="1440" alt="GKE_SA_KEY secret created 1" src="https://user-images.githubusercontent.com/53208269/204434515-686d146f-f14b-45e0-a605-72588d6505ef.png">
<img width="1440" alt="GKE_SA_KEY secret created 2" src="https://user-images.githubusercontent.com/53208269/204434524-32f0e43e-caf4-4fdd-90b3-b3156a3fcfc7.png">

## Trigger CD Deployment with new Github release
<img width="1440" alt="New Github release 1" src="https://user-images.githubusercontent.com/53208269/204434660-a9a5c46a-a27b-43a9-9e7f-98de72f90d01.png">
<img width="1440" alt="New Github release 2" src="https://user-images.githubusercontent.com/53208269/204434666-cb5e6d4f-626b-4963-858a-5672a827a147.png">
<img width="1440" alt="Release 2 3 building 1" src="https://user-images.githubusercontent.com/53208269/204434787-53ad7c2c-d14b-4974-b036-cfe96c32f7af.png">
<img width="1440" alt="Release 2 3 building 2" src="https://user-images.githubusercontent.com/53208269/204434797-a750f2b2-f4e7-4b13-83a9-532cd5fc2e65.png">
<img width="1440" alt="Release 2 3 building 3" src="https://user-images.githubusercontent.com/53208269/204434806-ece1c1b7-4ef6-450c-acab-64f8a000b9ac.png">
<img width="1440" alt="Release 2 3 build complete" src="https://user-images.githubusercontent.com/53208269/204434816-9c1a621e-efbb-47d9-a91b-6baa6a513937.png">
<img width="1440" alt="Release 2 3 build complete 2" src="https://user-images.githubusercontent.com/53208269/204434822-8a9e3c49-0f18-4c1f-8593-117f124895b0.png">

## GKE Workloads, Service, and Ingress
<img width="1440" alt="spring-gumball-deployment workload" src="https://user-images.githubusercontent.com/53208269/204434903-f7269551-46a7-4177-b072-b65319423688.png">
<img width="1440" alt="spring-gumball-service" src="https://user-images.githubusercontent.com/53208269/204434910-7cabf666-d9ab-48d9-8045-cadae8893aab.png">
<img width="1440" alt="spring-gumball-lb ingress" src="https://user-images.githubusercontent.com/53208269/204434935-eafc1cff-cc2c-48b4-ace4-53f20ec2d30b.png">

## Gumball App running from GKE
<img width="1440" alt="Gumball App running on GKE" src="https://user-images.githubusercontent.com/53208269/204435032-fcb162ad-7c39-4900-8146-2cfa406a57e5.png">

---

# spring-gumball ci/cd example

### This example demonstrates the following two GitHub Workflows.

* https://help.github.com/actions/language-and-framework-guides/building-and-testing-java-with-gradle

* https://github.com/google-github-actions/setup-gcloud/tree/master/example-workflows/gke

### Build Dependencies

* Gradle 5.6
* JDK 11

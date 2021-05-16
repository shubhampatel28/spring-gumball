# CMPE 172 - Lab #10 Notes

In this lab, we developed CI/CD workflow and delpoyed the spring gumball application too GKE.

## CI Workflow (Part 1)

Here, I set up the workflow to trigger on push and pr on main branch and optionally upload build artifact (i.e. jar file). 

I tested the workflow by making a change to the code and commit to main branch to trigger the action.

Here is the result of my action: 

![workflow](images/ci-workflow-1.png)

![workflow](images/ci-workflow-test-2.png)

![workflow](images/ci-workflow-test-3.png)

---

## CD Workflow (Part 2)

Here, I set up the CD pipeline for building and deploying the spring-gumball appliction to GKE. It triggers on "release."


* GCP Service Accoucnt & JSON Service Account Key

![gcp-service](images/gcp-service-account-4.png)

![gcp-service](images/gcp-service-key-5.png)


<br>

*  GitHub Action Secrets

![git-secret](images/git-secret-6.png)

<br>

* GKE Cluster Set up

![gke-cluser](images/cluster-gke-7.png)

<br>

* Git Relase Processes

![git-relase](images/git-release-8.png)

![git-relase](images/release-detials-9.png)

![git-relase](images/release-detials-9.png)

![git-relase](images/release-detials-9.png)

![git-relase](images/git-workflows-10.png)

![git-relase](images/git-cd-pipeline-workflow-11.png)

![git-relase](images/git-process-complete-12.png)

![git-relase](images/git-updated-workflow-13.png)

<br>

* Google Cloud

![google-cloud](images/worklaods-gke-14.png)

![google-cloud](images/services-gke-15.png)

![google-cloud](images/ingress-gke-16.png)

<br>


* Runninng Application

![google-cloud](images/gumball-application-17.png)





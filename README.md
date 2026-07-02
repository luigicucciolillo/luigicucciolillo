<!-- ![banner](banner_github.png)-->
![banner](banner_github.svg)

<!--# Learning ...
![Banner](https://images.unsplash.com/photo-1503023345310-bd7c1de61c7d?auto=format&fit=crop&w=1350&q=80)
![GitHub repo size](https://img.shields.io/github/repo-size/username/repo-name)
![License](https://img.shields.io/badge/license-MIT-blue)
[![Demo](https://img.shields.io/badge/Demo-Link-green)](https://your-demo-url.com)

## Masterclasses
-->
<details>
      <summary>
        <strong>[ONGOING] masterclass: Kubernetes Self healing, networking, HA large scale, Mesh, TLS ... </strong>
      </summary>
			<!-- 2 +++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++ -->
		<details style="margin:0; padding-left:1em;">
		  <summary style="margin: 0; padding: 0;">✅ 37 mins - Kubernetes Design Principles: Understand the Why - Saad Ali, Google</summary>
			&nbsp; <sub> 🔗 Link to YT: <a href="https://www.youtube.com/watch?v=ZuIQurh_kDk" target="_blank">here</a></sub><br>
  <blockquote style="margin:0; padding-left:1em;">
		    <sub>
		      Kubernetes is quickly becoming indispensable for managing and deploying workloads on distributed systems across both cloud and on-prem environments.  
		      While most people are now familiar with how to use Kubernetes, few are aware of the “why” behind it.  
		      Why does the Kubernetes API look the way it does?  
		      Why do Kubernetes components only interact with each other through the Kubernetes API?  
		      Why is there a PersistentVolumeClaim object when you could easily reference a volume directly from a pod?  
		      To answer these questions and help you develop a deeper understanding of Kubernetes, this talk exposes the principles underpinning the design of Kubernetes.  
		    </sub>  
		  </blockquote>
		</details>
<!-- 🔐 TLS Section ===================================================================== -->
<details style="margin:0.5em 0; padding-left:1em;">
  <summary style="cursor:pointer; font-weight:600; color:#0366d6;">
    ✅ <sub>About TLS and cert-manager</sub>
  </summary>
  <div style="margin-top:0.5em; padding-left:1em; line-height:1;">
	  <!-- TLS - TALK 1 +++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++ -->
    <p style="margin:0;">
      <sub>🔗 <b>cert-manager – Past, Present and Future</b> — 
      <i>Jake Sanders (cert-manager Maintainer) & Ashley Davis (Jetstack)</i>:
		      <a href="https://www.youtube.com/watch?v=yINv8RUkW-E" target="_blank">🎥 Watch here</a> | 
			  📄 <a href="https://github.com/luigicucciolillo/StudyMaterial/blob/main/Masterclasses/TLS/cert-manager%20-%20Past%2C%20Present%20and%20Future%20-%20Jake%20Sanders%2C%20cert-manager%20Maintainer%20%26%20Ashley%20Davis%20/slides.pdf" target="_blank">Slides</a> | 
		      🧾 <a href="https://github.com/luigicucciolillo/StudyMaterial/blob/main/Masterclasses/TLS/cert-manager%20-%20Past%2C%20Present%20and%20Future%20-%20Jake%20Sanders%2C%20cert-manager%20Maintainer%20%26%20Ashley%20Davis%20/text.pdf" target="_blank">Summary</a>
			  </sub>
		    </p>
			<blockquote style="margin:0.2em 0; padding-left:0.6em; border-left:2px solid #bbb; color:#666; font-size:0.85em; line-height:1.3;">
			  cert-manager is the Cloud Native way to manage X.509 certificates inside Kubernetes.  
			  It's often one of the first tools administrators install on a new cluster, reaching over
			  <b>15 million image pulls per day</b>!  
			  The project recently entered the CNCF incubation phase after two years in the sandbox.  
			  In this talk, two maintainers discuss why cert-manager matters, its evolution, and what’s next.
			</blockquote>
	  <!-- TLS - TALK 2 +++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++ -->
	      <p style="margin:0;">
            <sub>🔗 <b>Cert-Manager Beyond Ingress – Exploring the Variety of Use Cases - Matthew Bates, Jetstack</b> 
      <a href="https://www.youtube.com/watch?v=wEW2kVKxgss" target="_blank">🎥 Watch here</a></sub> | 
      📄 <a href="https://github.com/luigicucciolillo/StudyMaterial/blob/main/Masterclasses/TLS/Cert-Manager%20Beyond%20Ingress%20%E2%80%93%20Exploring%20the%20Variety%20of%20Use%20Cases%20-%20Matthew%20Bates%2C%20Jetstack%20/slides.pdf" target="_blank">Slides</a> | 
      🧾 <a href="https://github.com/luigicucciolillo/StudyMaterial/blob/main/Masterclasses/TLS/Cert-Manager%20Beyond%20Ingress%20%E2%80%93%20Exploring%20the%20Variety%20of%20Use%20Cases%20-%20Matthew%20Bates%2C%20Jetstack%20/text.pdf" target="_blank">Summary</a>
			  </sub>
		    </p>
			<blockquote style="margin:0.2em 0; padding-left:0.6em; border-left:2px solid #bbb; color:#666; font-size:0.85em; line-height:1.3;">
Cert-manager is a widely used project for the automation of X.509 TLS certificates. In 2020, it reached 1.0 and landed in the CNCF Sandbox. 
		cert-manager has been popularised by its support of ACME and Ingress, enabling many millions of certificates to be issued and renewed, 
		and to help secure the cloud native web with Kubernetes and all the various ingress controllers. But cert-manager, 
		with its custom resources and controllers, extensible with issuers including those out-of-tree, can also be used for a myriad of other 
		use cases in which certificates are required. This talk will walk through the various use cases for cert-manager, including ingress, control 
		plane and nodes (kubeadm, CAPI), webhooks, intra-service mTLS (cert-manager-csi) and service mesh (OpenServiceMesh, Istio).
			</blockquote>
	  <!-- TLS - TALK 3 +++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++ -->
	      <p style="margin:0;">
            <sub>🔗 <b>Best Friends Keep No Secrets: Going Secretless with cert-manager - Ashley Davis & Tim Ramlot, Venafi</b> 
      <a href="https://www.youtube.com/watch?v=VbCtDF8qlWA" target="_blank">🎥 Watch here</a></sub> | 
      📄 <a href="https://github.com/luigicucciolillo/StudyMaterial/blob/main/Masterclasses/TLS/Best%20Friends%20Keep%20No%20Secrets%3A%20Going%20Secretless%20with%20cert-manager%20-%20Ashley%20Davis%20%26%20Tim%20Ramlot%2C%20Venafi%20/slides.pdf" target="_blank">Slides</a> | 
      🧾 <a href="https://github.com/luigicucciolillo/StudyMaterial/blob/main/Masterclasses/TLS/Best%20Friends%20Keep%20No%20Secrets%3A%20Going%20Secretless%20with%20cert-manager%20-%20Ashley%20Davis%20%26%20Tim%20Ramlot%2C%20Venafi%20/text.pdf" target="_blank">Summary</a>
			  </sub>
		    </p>
			<blockquote style="margin:0.2em 0; padding-left:0.6em; border-left:2px solid #bbb; color:#666; font-size:0.85em; line-height:1.3;">
			In today's complex Kubernetes environments, managing secrets securely is a challenge. Traditional methods often involve complex configurations with secret vaults, secret syncing and secret backups. 
				Regardless of which fancy technology is used, secrets always come with a risk of being leaked. Most of the secrets used in traditional applications can be replaced by short-lived certificates. 
				Applications can prove to be the owner of a certificate without sharing any secrets. In Kubernetes, cert-manager can be used to provision these certificates to all applications without sharing any secret information. 
				Table of contents: - Do we actually need secrets? Comparing authentication methods: static secrets vs short-lived secrets and proof of ownership - H
				ow to issue certificates using cert-manager without using [S|s]ecrets - Compatibility and other challenges			
			</blockquote>
	  <!-- TLS - TALK X +++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++ -->
	      <p style="margin:0;">
            <sub>🔗 <b>title</b> 
      <a href="linkYT" target="_blank">🎥 Watch here</a></sub> | 
      📄 <a href="link slides" target="_blank">Slides</a> | 
      🧾 <a href="link text" target="_blank">Summary</a>
			  </sub>
		    </p>
			<blockquote style="margin:0.2em 0; padding-left:0.6em; border-left:2px solid #bbb; color:#666; font-size:0.85em; line-height:1.3;">
blablabla...
			</blockquote>
	  <!-- END TLS - TALK X +++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++ -->
		</details>
<!-- END TLS +++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++ -->
			<!-- 2 +++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++ -->
	<details style="margin:0; padding-left:1em;">
		  <summary style="margin: 0; padding: 0;"><sub>✅ - 35 mins -  Certifik8s: All You Need to Know About Certificates in Kubernetes [I] - Alexander Brand, Apprenda </sub></summary>
			&nbsp; <sub> 🔗 Link to YT: <a href="https://www.youtube.com/watch?v=gXz4cq3PKdg" target="_blank">here</a></sub><br>
  <blockquote style="margin:0; padding-left:1em;">
	  Certificates are an integral part of a secure Kubernetes cluster deployment. 
				They are mainly used to secure the Kubernetes API server using TLS,
				but certificates (and keys) are also used for other cluster functions such as client authentication,
				encryption of secrets, TLS bootstrapping, and the generation of service account tokens.<br>
			  Certificates pose interesting challenges to cluster operators. What does the certificate setup look like in an ideal scenario? 
				How long should certificates be valid for? 
				When nearing expiration dates, 
				how can certificates be rotated to ensure the cluster remains operational? 
				These challenges must be understood when it comes to deploying and operating a Kubernetes cluster.
				<br>
			  After this talk, you should have a better understanding of:
			  <br>&nbsp;&nbsp;&nbsp;&nbsp;• How each cluster component uses certificates for secure communications  
			  <br>&nbsp;&nbsp;&nbsp;&nbsp;• How certificates can be used for authentication, including service account tokens  
			  <br>&nbsp;&nbsp;&nbsp;&nbsp;• How the Kubelet TLS bootstrapping process works  
			  <br>&nbsp;&nbsp;&nbsp;&nbsp;• How to plan, generate and deploy the certificates required for a secure cluster  
			  <br>&nbsp;&nbsp;&nbsp;&nbsp;• How to rotate certificates that are nearing their expiration date  
			  <br><br>
			  <strong>About Alexander Brand</strong>  
			  Alex works on the Kismatic Enterprise Toolkit at Apprenda, making the deployment of production Kubernetes clusters easier. 
			He has been involved with Kubernetes and related projects since early 2016. Before Apprenda, 
			Alex attended Queen's University in Canada, where he majored in Biomedical Computing.
			</blockquote>
		</details>
	<sub> -<a href="https://www.youtube.com/watch?v=90kZRyPcRZw" target="_blank">
			   Kubernetes Deconstructed: Understanding Kubernetes by Breaking It Down - Carson Anderson, DOMO</a></sub><br>
	<sub> -<a href="https://www.youtube.com/watch?v=3KtEAa7_duA" target="_blank">
				  (5y ago) LISA19 - Deep Dive into Kubernetes Internals for Builders and Operators    </a></sub><br>
	<sub> -<a href="https://www.youtube.com/watch?v=S2BQz-5cboA" target="_blank">
				  (1y ago)  Crossplane Intro and Deep Dive - the Cloud Native Control Plane Framework </a></sub><br>
	Self Healing: <br> 
	<sub> -<a href="https://www.youtube.com/watch?v=91dgNqma7-Q" target="_blank">
				  (1y ago)        The Magic of Kubernetes Self-Healing Capabilities - Saad Ali, Google    </a></sub><br>
	<sub> -<a href="https://www.youtube.com/watch?v=bsrXifq3Pjc" target="_blank">
				  (8y ago)         Deploying Self Healing Services With Kubernetes w/ Rob Scott     </a></sub><br>
	<sub> -<a href="https://www.youtube.com/watch?v=3psxcNttPtA" target="_blank">
				  (1y ago)         "Kubernetes self-healing: HA for services and control plane"  - Lukasz Sztachanski i Lukasz Luczaj</a></sub><br>


<!--Networking-->

<details style="margin:0; padding-left:1em;">
		  <summary style="margin: 0; padding: 0;">Networking </summary>  
              <sub> -<a href="https://www.youtube.com/watch?v=Mj04QOqAaJ8" target="_blank">
                Understanding Kubernetes Networking in 30 Minutes - Ricardo Katz & James Strong  </a></sub><br>
        <sub> -<a href="https://www.youtube.com/watch?v=0Omvgd7Hg1I" target="_blank">
                Life of a Packet [I] - Michael Rubin, Google   </a></sub><br>
        <sub> -<a href="https://www.youtube.com/watch?v=InZVNuKY5GY" target="_blank">
                  Tutorial: Communication Is Key - Understanding Kubernetes Networking - Jeff Poole, Vivint Smart Home  </a></sub><br>
        <sub> -<a href="https://www.youtube.com/watch?v=920BZXvQpVs" target="_blank">
                Surviving Day 2 - How to Troubleshoot Kubernetes Networking - Thomas Graf, Isovalent </a></sub><br>
        <sub> -<a href="https://www.youtube.com/watch?v=tq9ng_Nz9j8" target="_blank">
              Kubernetes Networking Intro and Deep-Dive - Bowei Du & Tim Hockin, Google </a></sub><br>
        <sub> -<a href="https://www.youtube.com/watch?v=B6FsWNUnRo0&list=PLSAko72nKb8QWsfPpBlsw-kOdMBD7sra-" target="_blank">
                Understanding Kubernetes Networking. Part 1: Container Networking  </a></sub><br>
		</details>
                        <!-- 2 +++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++ -->
                      <details style="margin:0; padding-left:1em;">
                        <summary style="margin: 0; padding: 0;">✅ Tutorial: From CNI Zero to CNI Hero: A Kubernetes Networking Tutorial Using CNI </summary>
                        &nbsp; <sub> 🔗 Link to YT: <a href="https://www.youtube.com/watch?v=YumoKGhuZ2o" target="_blank">here</a></sub><br>
                  <a href="https://github.com/luigicucciolillo/StudyMaterial/tree/main/Masterclasses/CNI/%20Tutorial%3A%20From%20CNI%20Zero%20to%20CNI%20Hero%3A%20A%20Kubernetes%20Networking%20Tutorial%20Using%20CNI%20" target="_blank">
                            material available here:</a><br>
                  <a href="https://github.com/luigicucciolillo/cni-hero-hands-on" target="_blank">
                            fork of demo</a><br> 
                      </details>
<!--HA Large scale-->

<details style="margin:0; padding-left:1em;">
		  <summary style="margin: 0; padding: 0;">HA Large scale </summary>  <blockquote style="margin:0; padding-left:1em;">
	<sub> -<a href="https://www.youtube.com/watch?v=NpT9RraqKdY" target="_blank">
				Highly Available Kubernetes Clusters - Best Practices - Meaghan Kjelland & Karan Goel, Google </a></sub><br>
	<sub> -<a href="https://www.youtube.com/watch?v=AYNaaXlV8LQ" target="_blank">
				  (1y ago)      Building a Large Scale Multi-Cloud Multi-Region SaaS Platform with Kubernetes Controllers </a></sub><br>
	<sub> -<a href="https://www.youtube.com/watch?v=WRACr5nXl9U" target="_blank">
				  (1y ago)      Architecting Resilience: Lessons from Managing 7K+ Kubernetes Clusters at Scale  </a></sub><br>
		  </blockquote>
		</details>
<!--Mesh: Istio and Cilium:-->
<details style="margin:0; padding-left:1em;">
		  <summary style="margin: 0; padding: 0;">Mesh: Istio and Cilium:</summary>  
      <blockquote style="margin:0; padding-left:1em;">
        <sub> -<a href="https://www.youtube.com/watch?v=bEFILWrRJJ4" target="_blank">
                (5y ago)         Demystifying Service Mesh, HashiCorp   </a></sub><br>
        <sub> -<a href="https://www.youtube.com/watch?v=91oylZSoYzM" target="_blank">
                (1y ago) Comparing Sidecar-Less Service Mesh from Cilium and Istio - Christian Posta, Solo.io </a></sub><br>
        <sub> -<a href="https://www.youtube.com/watch?v=qbB3TEiOb24" target="_blank">
                (1y ago)    Simplifying Multi-Cluster and Multi-Cloud Deployments with Cilium - Liz Rice, Isovalent </a></sub><br>
        <sub> -<a href="https://www.youtube.com/watch?v=x2qemf9Wmqo" target="_blank">
                (1y ago)  Istio Ambient Service Mesh Made Simple - Lin Sun, Solo.io </a></sub><br>
        <sub> -<a href="https://www.youtube.com/watch?v=xTUiXLqfJms" target="_blank">
                (1y ago)   Best-Practices for Securing Egress Traffic with Istio - Niranjan Shankar, Microsoft </a></sub><br>
        <sub> -<a href="https://www.youtube.com/watch?v=XW10IpsTmH8" target="_blank">
                (6mm ago)    What Istio Got Wrong: Learnings from the Last Seven Years of Service Mesh - C. Posta, L. Ryan  </a></sub><br>
        <sub> -<a href="https://www.youtube.com/watch?v=XW10IpsTmH8" target="_blank">
                (1y ago)     Reliable multi-cluster application architectures with Istio - Ameer Abbas & John Howard, Google </a></sub><br>
        <sub> -<a href="https://www.youtube.com/watch?v=qbB3TEiOb24" target="_blank">
                (1y ago)     What Istio Got Wrong: Learnings from the Last Seven Years of Service Mesh - C. Posta, L. Ryan </a></sub><br>
        <sub> -<a href="https://www.youtube.com/watch?v=_8FNsvoECPU" target="_blank">
                (1y ago)       Create resilient multi-cluster, multi-regional and multi-tenant architectures with Istio and K8s   </a></sub><br>
		  </blockquote>
</details>
  <details>
    <summary>
      <strong> &emsp; 06/25 - 🟢 - Kubernetes troubleshooting: a step-by-step guide </strong>
    </summary>
      &emsp;- 2 hours - 🟢 - <a href="https://trainingportal.linuxfoundation.org/learn/course/kubernetes-troubleshooting-a-step-by-step-guide/main/kubernetes-troubleshooting-a-step-by-step-guide?page=1" target="_blank">Link here</a><br>
  Explaination and analysis (with Devtron) of the following common errors, their possible root causes and how to fix them:<br>
      - CRASHLOOPBACKOFF<br>
      -- OOMKilled<br>
      -- CPU throttling<br>
      - ENV Variables/Secrets Mount Issue<br> 
      - Database connection issues
      FROM The Linux Foundation
  </details>
</details>

<details open><summary><strong>Cloud Engineering, Web development and DevOps</strong></summary>
<!-- START Cyber Security super bundle-->    
<ul>
<li>
    <details>
      <summary>
        <strong>04/26 -> Actual - 🟡 - 
                  <a href="https://github.com/luigicucciolillo/Certifications/tree/main/The%20linux%20foundation/Cybersecurity%20Super%20Bundle" target="_blank">
            Cyber Security super bundle  </a>
            </strong>
      </summary> 
      &emsp;
      - 60 hours - 🟡 - 
        <a href="https://github.com/luigicucciolillo/Certifications/tree/main/The%20linux%20foundation" target="_blank">
            Linux System Administration Essentials (LFS207) </a>
            <br>
            &emsp;
      - 35 hours - 🟢 - 
        <a href="https://github.com/luigicucciolillo/Certifications/tree/main/The%20linux%20foundation/Kubernetes%20fundamentals%20LFS258" target="_blank">
            Kubernetes Fundamentals (LFS258) </a><br>
            &emsp;
      - 30 hours - 🛑 - 
        <a href="https://github.com/luigicucciolillo/Certifications/tree/main/The%20linux%20foundation" target="_blank">
            Kubernetes Security Essentials (LFS260) </a><br>
            &emsp;
      - 40 hours - 🛑 - 
        <a href="https://github.com/luigicucciolillo/Certifications/tree/main/The%20linux%20foundation" target="_blank">
            Implementing DevSecOps (LFS262) </a><br>
            &emsp;
      - 24 hours - 🛑 - 
        <a href="https://github.com/luigicucciolillo/Certifications/tree/main/The%20linux%20foundation" target="_blank">
            Mastering Infrastructure Security: Strategies, Tools, and Practices (SKF200) </a><br>
            &emsp;
      - 35 hours - 🛑 - 
        <a href="https://github.com/luigicucciolillo/Certifications/tree/main/The%20linux%20foundation" target="_blank">
            Mastering Kubernetes Security with Kyverno (LFS255) </a><br>
	  </details>
</li>
<!-- END Cyber Security super bundle--> 
<!-- START Advanced Cloud Engineer IT Professional Program (LFS002)-->
<li>
    <details>
      <summary>
        <strong>06/25 -> 03/26 - 🟢🎓 - 
          <a href="https://github.com/luigicucciolillo/Certifications/tree/main/The%20linux%20foundation/Advanced%20Cloud%20Engineer%20IT%20Professional%20Program%20Logistics%20(LFS002)" target="_blank">
            Advanced Cloud Engineer IT Professional Program (LFS002) <br>
          </a>
        </strong>
      </summary>
            &emsp;- 40 hours - 🟢 - <a href="https://github.com/luigicucciolillo/Certifications/tree/main/The%20linux%20foundation/Containers%20Fundamentals%20LFS253" target="_blank">Containers Fundamentals (LFS253)</a><br>
            &emsp;- 35 hours - 🟢 - <a href="https://github.com/luigicucciolillo/Certifications/tree/main/The%20linux%20foundation/Kubernetes%20fundamentals%20LFS258" target="_blank">Kubernetes Fundamentals (LFS258)</a><br>
            &emsp;- 20 hours - 🟢 - <a href="https://github.com/luigicucciolillo/Certifications/tree/main/The%20linux%20foundation/Service%20Mesh%20fundamentals%20LFS243" target="_blank">Service Mesh Fundamentals (LFS243)</a><br>
            &emsp;- 25 hours - 🟢 - <a href="https://github.com/luigicucciolillo/Certifications/tree/main/The%20linux%20foundation/Monitoring%20Systems%20and%20Services%20with%20Prometheus%20LFS241" target="_blank">Monitoring Systems and Services with Prometheus (LFS241)</a><br>
            &emsp;- 30 hours - 🟢 - <a href="https://github.com/luigicucciolillo/Certifications/tree/main/The%20linux%20foundation/Managing%20Kubernetes%20Applications%20with%20Helm%20LFS244" target="_blank">Managing Kubernetes Applications with Helm (LFS244)</a><br>
			      &emsp;- 30 hours - 🟢 - <a href="https://github.com/luigicucciolillo/Certifications/tree/main/The%20linux%20foundation/Cloud%20Native%20Logging%20with%20Fluentd%20and%20Fluent%20Bit%20LFS242" target="_blank">Cloud Native Logging with Fluentd and Fluent Bit (LFS242)</a><br>
    </details>
</li>
<!-- END Advanced Cloud Engineer IT Professional Program (LFS002) -->    
<!-- START Introduction to DevOps and Cloud Infrastructure Technologies-->
<li>
    <details>
      <summary>
        <strong>05/25 -> 06/25 - 🟢🎓 -
          <a href="https://github.com/luigicucciolillo/Certifications/tree/main/The%20linux%20foundation/Introduction%20to%20DevOps%20and%20Cloud%20Infrastructure%20Technologies" target="_blank">
          Introduction to DevOps and Cloud Infrastructure Technologies</a>
        </strong>
      </summary>
            &emsp;- 20 hours - 🟢 - <a href="https://github.com/luigicucciolillo/Certifications/tree/main/The%20linux%20foundation/Introduction%20to%20Jenkins%20LFS167" target="_blank">Introduction to Jenkins (LFS167)</a><br>
            &emsp;- 20 hours - 🟢 - <a href="https://github.com/luigicucciolillo/Certifications/tree/main/The%20linux%20foundation/Introduction%20to%20Kubernetes%20LFS158" target="_blank">Introduction to kubernetes (LFS158)</a><br>
            &emsp;- 50 hours - 🟢 - <a href="https://github.com/luigicucciolillo/Certifications/tree/main/The%20linux%20foundation/Introduction%20to%20Cloud%20Infrastructure%20Technologies%20LFS151" target="_blank">Introduction to Cloud Infrastructure Technologies (LFS151)</a><br>
            &emsp;- 12 hours - 🟢 - <a href="https://github.com/luigicucciolillo/Certifications/tree/main/The%20linux%20foundation/Introduction%20to%20DevOps%20and%20Site%20Reliability%20Engineering%20LFS162" target="_blank">Introduction to DevOps and Site Reliability Engineering (LFS162)</a><br>
    </details>
</li>
<!-- END Introduction to DevOps and Cloud Infrastructure Technologies-->           
<li>
    <details>
      <summary>
        <strong>06/24 -> 04/25 - 🟢🎓 -  Full stack web development and DevOps
        </strong>
      </summary>
            &emsp;- 03/25 -> 04/25 - 🟢🎓 - <a href="https://github.com/luigicucciolillo/Certifications/tree/main/DevOps%20with%20Docker%20-%20Helsinki%20University" target="_blank">DevOps with Docker</a> - 3 ECTS from University of Helsinki<br>
            &emsp; &emsp;<sub><a href="https://education.ec.europa.eu/it/education-levels/higher-education/inclusive-and-connected-higher-education/european-credit-transfer-and-accumulation-system" target="_blank">ECTS</a>= European Credit Transfer and Accumulation System (ECTS)</sub><br>
            &emsp;- 02/25 -> 03/25 - 🟠   - <a href="https://www.udemy.com/course/nodejs-the-complete-guide/?srsltid=AfmBOopQY5H91x0__bmJZcLIRDGMmQbi0X5WQE4TGY3kSHFZlXlJtYsC&couponCode=LETSLEARNNOW" target="_blank">NodeJS - The Complete Guide (MVC, REST APIs, GraphQL, Deno)</a> - Udemy<br>
            &emsp;- 06/24 -> 01/25 - 🟢🎓 - <a href="https://github.com/luigicucciolillo/Certifications/tree/main/Nuclio%20digital%20school/Full%20stack%20development%20-%20Nuclio%20digital%20school" target="_blank">Full Stack Web Development Course</a> - Nuclio Digital School<br>
    </details>
</li>
</ul>
</details>
<!--Courses and workshops on Agile management, Project management and foundraising-->
<details>
  <summary><strong>Fundraising, Agile methodologies and Project management</strong></summary>
  <ul>
    <li>
      <details>
        <summary><strong>09/25 –> 11/25 - 🟢 Clean Tech Academy</strong></summary>
        3 months -
        <a href="https://github.com/luigicucciolillo/Certifications/tree/main/Clean%20Tech%20Academy">more info here</a><br>
        From: Miticoro Foundation
      </details>
    </li>
    <li>
      <details>
        <summary><strong>10/25 - 🟢 Designing in Italy for Global Citizenship</strong></summary>
        35 hours -
        <a href="https://github.com/luigicucciolillo/Certifications/tree/main/Progeu/EuroProgettazione">more info here</a><br>
        Covered EU funding programmes and project-management tools, including Next Generation EU, Cohesion Policy, Horizon Europe, PM², LFA, RACI, SWOT, stakeholder mapping and SMART indicators.<br>
        From: ProgEU — Progress in European Union
      </details>
    </li>
    <li>
      <details>
        <summary><strong>05/25 - 🟢 Agile Management</strong></summary>
        16 hours -
        <a href="https://github.com/luigicucciolillo/Certifications/tree/main/Nuclio%20digital%20school/Agile%20management">more info here</a><br>
        Intensive four-week programme covering Agile methodologies, digital product management and team management.<br>
        From: Nuclio Digital School
      </details>
    </li>
  </ul>
</details>


</details>

<!--
## Other courses
<table border="1" cellspacing="0" cellpadding="8">
  <thead> <tr> <th>Course</th>  <th>Date</th>  <th>Institution</th>  <th>Lenght</th>  <th> - </th> </tr> </thead>
  <tbody>
   <tr>
      <td><a href="https://www.coursera.org/specializations/cloud-native-development-openshift-kubernetes" target="_blank">
        Cloud-Native Development with OpenShift and Kubernetes</a></td>
	      <td>?/25</td>
	      <td>Red Hat/ Coursera</td>
	      <td> 1 month</td>
	      <td>🛑💬³</td>
    </tr> 
-->
 <!--    <tr>
      <td><a href="https://devopswithkubernetes.com/" target="_blank">
        DevOps with kubernetes</a></td>
	      <td>06/25</td>
	      <td>University of Helsinki</td>
	      <td>5 ECTS</td>
	      <td>🛑💬²</td>
    </tr>
-->   
<!-- <tr>
  <td><a href="https://github.com/luigicucciolillo/Certifications/tree/main/Progeu/EuroProgettazione" target="_blank">
    Designing in Italy for Global Citizenship</a></td>
    <td>10/25</td>
    <td>ProgEU: Progress in European Union</td>
    <td>35 hours</td>
<td>🟢🎓</td>
</tr>
-->
  <!-- <tr>
      <td><a href="https://github.com/luigicucciolillo/Certifications/tree/main/ProfessionAI/Fine-tuning%20%26%20Deploy%20di%20un%20LLM" target="_blank">
        Fine tuning and deploy of a LLM</a></td>
	      <td>06/25</td>
	      <td>ProfessionAI</td>
	      <td>2 hours</td>
	      <td>🟢</td>
    </tr>   
	  <tr>
    -->
  <!--AI Cloud Explained: What It Is, Why It Matters, and How It Works
  <tr>
   <td>
    <details>
      <summary>
        <strong> AI Cloud Explained: What It Is, Why It Matters, and How It Works </strong>
      </summary>
	    Link to official course 
      <a href="https://trainingportal.linuxfoundation.org/learn/course/ai-cloud-explained-what-it-is-why-it-matters-and-how-it-works/main/ai-cloud-explained-what-it-is-why-it-matters-and-how-it-works" target="_blank">
        here</a><br>
		Explore how AI Cloud revolutionizes AI workloads by providing scalable computing, seamless integration, and real-time processing. Learn how this powerful infrastructure enables businesses to optimize AI model training, deployment, and performance with efficiency and flexibility.
    </details>
          </td>
	  	      <td>06/25</td>
	  <td>The Linux Foundation</td>
	      <td>2 hours</td>
	      <td>🟢</td>
    </tr>

  -->
<!--  </td>
</tr>  
	<tr>
  <tr>
   <td>
    <details>
      <summary>
        <strong>Kubernetes troubleshooting: a step-by-step guide </strong>
      </summary>
	    Link to official course 
      <a href="https://trainingportal.linuxfoundation.org/learn/course/kubernetes-troubleshooting-a-step-by-step-guide/main/kubernetes-troubleshooting-a-step-by-step-guide?page=1" target="_blank">
        here</a><br>
		Explaination and analysis (with Devtron) of the following common errors, their possible root causes and how to fix them:<br>
		   - CRASHLOOPBACKOFF<br>
		   -- OOMKilled<br>
		   -- CPU throttling<br>
		   - ENV Variables/Secrets Mount Issue<br> 
		   - Database connection issues
    </details>
          </td>
	  	      <td>06/25</td>
	  <td>The Linux Foundation</td>
	      <td>2 hours</td>
	      <td>🟢</td>
    </tr>
  -->
<!--  </td>
</tr> 
--> 
<!--
<tr><td><a href="https://github.com/luigicucciolillo/Certifications/tree/main/Nuclio%20digital%20school/workshop%20-%20crea%20tu%20applicacion%20que%20usa%20inteligencia%20artificial" target="_blank">
        Desarrolla una Aplicación Web con Inteligencia Artificial Usando Endpoints de API (OpenAI)</a></td><td>05/25</td><td>Nuclio Digital School</td><td>4 hours</td><td>🟢🛠️</td>
</tr>
-->
<!--
<tr><td> <a href="https://github.com/luigicucciolillo/Certifications/tree/main/Nuclio%20digital%20school/Agile%20management" target="_blank">
	Agile management</a> </td><td>05/25</td> <td>Nuclio digital school</td> <td> 16 hours </td> <td>🟢🎓</td>
</tr>
-->
<!-- reformatting ------------------------------------------------>

<!--
<tr>
   <td>
    <details>
      <summary>
        <strong> Masterclasses on Knative </strong>
      </summary> 
<table style="width: 100%; margin-top: 10px;">
	  <tr>
      <td>
        <a href="https://github.com/luigicucciolillo/StudyMaterial/tree/main/Masterclasses/Knative" target="_blank">
          Masterclasses on Knative
        </a>
        <br>
        <sub> - 
        <a href="https://github.com/luigicucciolillo/StudyMaterial/tree/main/Masterclasses/Knative/Knative%20A%20Kubernetes%20Framework%20to%20Manage%20Serverless%20Workloads%20by%20Nikhil%20Barthwal%2C%20Google" target="_blank">
          Knative: A Kubernetes Framework to Manage Serverless Workloads
        </a>
        </sub> 
        <br>
        <sub> - 
        <a href="https://github.com/luigicucciolillo/StudyMaterial/tree/main/Masterclasses/Knative/Unleashing%20the%20Power%20of%20Serverless%20on%20Kubernetes%20with%20Knative%2C%20Crossplane%2C%20Dapr%20%26%20KEDA" target="_blank">
          Unleashing the Power of Serverless on Kubernetes with Knative,Crossplane,Dapr
        </a>
        </sub> 
        <br>
        <sub> - 
        <a href="https://github.com/luigicucciolillo/StudyMaterial/tree/main/Masterclasses/Knative/Use%20Knative%20When%20You%20Can%2C%20and%20Kubernetes%20When%20You%20Must" target="_blank">
          Use Knative When You Can, and Kubernetes When You Must
        </a>
        </sub> 
        <br>
        <sub> - 
        <a href="https://github.com/luigicucciolillo/StudyMaterial/tree/main/Masterclasses/Knative/Corso%20Knative%2C%20a%20serverless%20environment%20for%20Kubernetes%20Lui" target="_blank">
          Corso Knative, a serverless environment for Kubernetes
        </a>
        </sub> 
        <br>
        <sub> - 
        <a href="https://github.com/luigicucciolillo/StudyMaterial/tree/main/Masterclasses/Knative/Inside%20Knative%20Serving%20-%20Dominik%20Tornow%2C%20SAP%20%26%20Andrew%20Chen%2C%20Google" target="_blank">
          Inside Knative Serving
        </a>
        </sub> 
        <br>
      </td>
      <td>05/25</td>
      <td>
        <br>
        <sub> Barthwal, Google </sub>
        <br>
        <sub> Salatino, Diagrid.io</sub>
      <br>
      <sub> Hadas & Maximilien, IBM</sub>
      <br>
      <sub> Leoni, Sorint lab</sub>
      <br>
      <sub> Tornow&Chen, SAP&Google</sub>
      <br>
      </td>
      <td>3h 15m</td>
      <td>🟢⚡</td>
    </tr>
	      </table>
	</details>
          </td>
	  	      <td>06/25</td>
	  <td> 3+ </td>
	      <td> 3h15m </td>
	      <td>🟢</td>
    </tr>
  </td>
</tr>
 ------------------------------------------------------------------------------------------- -->
<!--
 <tr>
   <td>
    <details>
      <summary>
        <strong> Kubernetes masterclass from Rancher Labs  </strong>
      </summary> 
      <table style="width: 100%; margin-top: 10px;">
	        <thead>
    <tr>
      <th>Course</th>
      <th>Date</th>
      <th>Institution</th>
      <th>Lenght</th>
      <th> - </th>
    </tr>
  </thead>
  <tr>
      <td><a href="https://github.com/luigicucciolillo/StudyMaterial/tree/main/Masterclasses/Kubernetes%20masterclass%20from%20Rancher" target="_blank">
	  Kubernetes masterclass from Rancher Labs</a><br>
        <sub> - <a href="https://github.com/luigicucciolillo/StudyMaterial/tree/main/Masterclasses/Kubernetes%20masterclass%20from%20Rancher" target="_blank">
          Intro to kubernetes and rancher</a></sub><br>
        <sub> - <a href="https://github.com/luigicucciolillo/StudyMaterial/tree/main/Masterclasses/Kubernetes%20masterclass%20from%20Rancher/1%20-%20Intro%20to%20K3s%20Online%20Training%20Lightweight%20Kubernetes" target="_blank">
          Intro to K3s Online Training: Lightweight Kubernetes   </a></sub><br>
        <sub> - <a href="https://github.com/luigicucciolillo/StudyMaterial/tree/main/Masterclasses/Kubernetes%20masterclass%20from%20Rancher/2%20-%20Kubernetes%20Master%20Class%20Understanding%20and%20Implementing%20Service%20Mesh" target="_blank"> Understanding and Implementing Service Mesh</a> </sub><br>
        <sub> - <a href="https://github.com/luigicucciolillo/StudyMaterial/tree/main/Masterclasses/Kubernetes%20masterclass%20from%20Rancher/3%20-%20Kubernetes%20Master%20Class%20Monitoring%20and%20Alerting%20with%20Prometheus%20%26%20Grafana" target="_blank">Monitoring and Alerting with Prometheus & Grafana</a></sub><br>
      </td>
      <td>05/25</td>
      <td>
        Rancher Labs
      </td>
      <td> 6 hours</td>
      <td>🟢⚡</td>
    </tr>
	</table>
	</details>
          </td>
	  	      <td>05/25</td>
	  <td>Rancher Labs</td>
	      <td> 6 hours</td>
	      <td>🟢⚡</td>
    </tr>
  </td>
</tr> 
 ------------------------------------------------------------------------------------------- -->


 <!-- </tbody>
</table>
-->
<!--
<sub> 
🟢 = completed | 
🟡 = started |
🟠 = stopped |
🔵 = ... |
🛑 = blocked/ waiting to start |
🎓 = course |
🛠️ = workshop |
⚡ = masterclass
-->
<!--
<sub> 
💬³ = On the bucket list, to start asap <br>
💬² = DevOps with kubernetes starts in june <br>
💬¹ = NodeJS ... Stopped to follow others <br>
</sub>
-->
<!--
**Resume** : 
<a href="https://github.com/luigicucciolillo/Certifications/blob/main/resume/CV_cucciolillo.pdf" target="_blank">
here
</a>
<br>
-->
**badges** : 
<a href="https://www.credly.com/users/luigi-cucciolillo/badges#credly" target="_blank">
here
</a>

<!--
**luigicucciolillo/luigicucciolillo** is a ✨ _special_ ✨ repository because its `README.md` (this file) appears on your GitHub profile.
💬¹  💬²  💬³  💬⁴  💬⁵
- 🔭 🌱 👯 🤔 💬 📫 😄 ⚡ 

Wishlist:
https://www.coursera.org/learn/npp-linux-networking

https://www.coursera.org/learn/applications-development-microservices-serverless-openshift
https://www.coursera.org/learn/advanced-kubernetes-third-course-3
https://www.coursera.org/specializations/cloud-computing

https://www.coursera.org/projects/pod-management-with-kubernetes-run-containerized-workloads
https://www.coursera.org/projects/scaling-e-commerce-with-kubernetes-deploy-web-apps
-->

<table>
  <tr>
    <td valign="top">
      <details>
        <summary><strong>AI</strong></summary>
          <details>
          <summary><strong>06/25 - 🟢 - Fine-tuning and Deploy of a LLM</strong></summary>
          2 hours - 🟢 -
          <a href="https://github.com/luigicucciolillo/Certifications/tree/main/ProfessionAI/Fine-tuning%20%26%20Deploy%20di%20un%20LLM">Link here</a><br>
          From: ProfessionAI
          </details>
          <details>
          <summary><strong>06/25 - 🟢 - AI Cloud Explained: What It Is, Why It Matters, and How It Works</strong></summary>
          2 hours - 🟢 -
          <a href="https://trainingportal.linuxfoundation.org/learn/course/ai-cloud-explained-what-it-is-why-it-matters-and-how-it-works/main/ai-cloud-explained-what-it-is-why-it-matters-and-how-it-works">Link here</a><br>
          Explored scalable AI workloads, model training, deployment, and real-time processing in cloud environments.
          </details>
          <details>
          <summary><strong>05/25 - 🟢 - Desarrolla una Aplicación Web con Inteligencia Artificial Usando Endpoints de API OpenAI</strong></summary>
          4 hours - 🟢 -
          <a href="https://github.com/luigicucciolillo/Certifications/tree/main/Nuclio%20digital%20school/workshop%20-%20crea%20tu%20applicacion%20que%20usa%20inteligencia%20artificial">Link here</a><br>
          Built a web application using AI API endpoints, focusing on practical OpenAI integration.<br>
          From: Nuclio Digital School
          </details>
          <details>
          <summary><strong>04/25 - 🟢🛠️ - Aprende a analizar datos con IA generativa</strong></summary>
          3 hours - 🟢 -
          <a href="https://github.com/luigicucciolillo/Certifications/tree/main/Nuclio%20digital%20school/workshop%20-%20Aprende%20a%20analizar%20datos%20con%20IA%20generativa">More info here</a><br>
          From: Nuclio Digital School
          </details>
          <details>
          <summary><strong>05/25 - 🟢🛠️ - IA sin código + Power BI: Crea, visualiza y decide con datos</strong></summary>
          3 hours - 🟢 -
          <a href="https://github.com/luigicucciolillo/Certifications/tree/main/Nuclio%20digital%20school/workshop%20-%20IA%20sin%20codigo%20%2B%20power%20BI">More info here</a><br>
          From: Nuclio Digital School
          </details>
          <details>
          <summary><strong>10/25 - 🟢🛠️ - Open Week: AI Development/Engineering Workshop</strong></summary>
          6 hours - 🟢 -
          <a href="https://github.com/luigicucciolillo/Certifications/tree/main/ProfessionAI/AI%20engineering%3A%20From%20model%20to%20service%2C%20how%20to%20serve%20a%20model%20through%20a%20REST%20API.">More info here</a><br>
          3h - From Model to Service: Deploying ML Models as REST APIs<br>
          3h - Expense Manager Agent with Telegram<br>
          From: Nuclio Digital School
          </details>
      </details>
    </td>
    <td valign="top">
      <details>
        <summary><strong>K8s</strong></summary>
        <details>
          <summary><strong>Masterclasses on Knative</strong></summary>
          <a href="https://github.com/luigicucciolillo/StudyMaterial/tree/main/Masterclasses/Knative">Masterclasses on Knative</a><br>
            <sub>05/25 · 3h 15m · 🟢⚡</sub><br><br>
            <sub>• <a href="https://github.com/luigicucciolillo/StudyMaterial/tree/main/Masterclasses/Knative/Knative%20A%20Kubernetes%20Framework%20to%20Manage%20Serverless%20Workloads%20by%20Nikhil%20Barthwal%2C%20Google">Knative: A Kubernetes Framework to Manage Serverless Workloads</a></sub><br>
            <sub>Barthwal, Google</sub><br><br>
            <sub>• <a href="https://github.com/luigicucciolillo/StudyMaterial/tree/main/Masterclasses/Knative/Unleashing%20the%20Power%20of%20Serverless%20on%20Kubernetes%20with%20Knative%2C%20Crossplane%2C%20Dapr%20%26%20KEDA">Unleashing the Power of Serverless on Kubernetes with Knative, Crossplane, Dapr and KEDA</a></sub><br>
            <sub>Salatino, Diagrid.io</sub><br><br>
            <sub>• <a href="https://github.com/luigicucciolillo/StudyMaterial/tree/main/Masterclasses/Knative/Use%20Knative%20When%20You%20Can%2C%20and%20Kubernetes%20When%20You%20Must">Use Knative When You Can, and Kubernetes When You Must</a></sub><br>
            <sub>Hadas &amp; Maximilien, IBM</sub><br><br>
            <sub>• <a href="https://github.com/luigicucciolillo/StudyMaterial/tree/main/Masterclasses/Knative/Corso%20Knative%2C%20a%20serverless%20environment%20for%20Kubernetes%20Lui">Corso Knative, a Serverless Environment for Kubernetes</a></sub><br>
            <sub>Leoni, Sorint Lab</sub><br><br>
            <sub>• <a href="https://github.com/luigicucciolillo/StudyMaterial/tree/main/Masterclasses/Knative/Inside%20Knative%20Serving%20-%20Dominik%20Tornow%2C%20SAP%20%26%20Andrew%20Chen%2C%20Google">Inside Knative Serving</a></sub><br>
            <sub>Tornow &amp; Chen, SAP &amp; Google</sub>
        </details>
        <details>
          <summary><strong>Kubernetes Masterclass from Rancher Labs</strong></summary>
          <a href="https://github.com/luigicucciolillo/StudyMaterial/tree/main/Masterclasses/Kubernetes%20masterclass%20from%20Rancher">Kubernetes Masterclass from Rancher Labs</a><br>
            <sub>05/25 · Rancher Labs · 6 hours · 🟢⚡</sub><br><br>
            <sub>• <a href="https://github.com/luigicucciolillo/StudyMaterial/tree/main/Masterclasses/Kubernetes%20masterclass%20from%20Rancher">Intro to Kubernetes and Rancher</a></sub><br>
            <sub>• <a href="https://github.com/luigicucciolillo/StudyMaterial/tree/main/Masterclasses/Kubernetes%20masterclass%20from%20Rancher/1%20-%20Intro%20to%20K3s%20Online%20Training%20Lightweight%20Kubernetes">Intro to K3s Online Training: Lightweight Kubernetes</a></sub><br>
            <sub>• <a href="https://github.com/luigicucciolillo/StudyMaterial/tree/main/Masterclasses/Kubernetes%20masterclass%20from%20Rancher/2%20-%20Kubernetes%20Master%20Class%20Understanding%20and%20Implementing%20Service%20Mesh">Understanding and Implementing Service Mesh</a></sub><br>
            <sub>• <a href="https://github.com/luigicucciolillo/StudyMaterial/tree/main/Masterclasses/Kubernetes%20masterclass%20from%20Rancher/3%20-%20Kubernetes%20Master%20Class%20Monitoring%20and%20Alerting%20with%20Prometheus%20%26%20Grafana">Monitoring and Alerting with Prometheus &amp; Grafana</a></sub>
        </details>
      </details>
    </td>
  </tr>
</table>

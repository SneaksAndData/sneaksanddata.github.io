---
_layout: landing
title: Ecco Sneaks&Data Services suite
tagline: Set of scalable open-source solutions for building data platform
---

<style>
.btn-coming-soon {
  background: rgb(128,128,128);
  cursor: not-allowed;
  pointer-events: none;
}

[data-bs-theme='dark'] .txt-coming-soon {
  color: rgb(227,255,215);
  border-style: dotted;
  border-radius: 7px;
}

.txt-coming-soon {
  color: rgb(0,0,0);
  border-style: dotted;
  border-radius: 7px;
}

.column {
  float: left;
  width: 25%;
}

.description {
    margin-bottom: 50px;
}

.descriptions {
    margin-top: 150px;
}

/* Clear floats after the columns */
.row:after {
  content: "";
  display: table;
  clear: both;
}

</style>

<div align="center">
    <h1 style="margin-bottom: 150px;">Ecco Data platform</h1>
    <div class="row">
         <div class ="column">
            <img src="images/arcane-logo.png" width="100" height="100">
            <div style="margin-top: 15px">
            <a class="btn btn-lg btn-primary" href="/arcane-docs">Arcane</a>
            <p>Scalable Data Streaming Framework</p>
            </div>
        </div>
         <div class ="column">
            <img src="images/beast-logo.png" width="100" height="100">
            <div style="margin-top: 15px">
            <a class="btn btn-coming-soon" href="/beast-docs">Beast</a>
            <p>Serverless Apache Spark</p>
            </div>
            <p class="txt-coming-soon">Coming soon</p>
        </div>
         <div class ="column">
            <img src="images/crystal-logo.png" width="100" height="100">
            <div style="margin-top: 15px">
            <a class="btn btn-coming-soon" href="/crystal-docs">Crystal</a>
            <p>Serverless AI/ML Execution Framework</p>
            </div>
            <p class="txt-coming-soon">Coming soon</p>
        </div>
         <div class ="column">
            <img src="images/boxer-logo.png" width="100" height="100">
            <div style="margin-top: 15px">
            <a class="btn btn-coming-soon" href="/boxer-docs">Boxer</a>
            <p>JWT-Based Authorization API</p>
            </div>
            <p class="txt-coming-soon">Coming soon</p>
        </div>
    </div>
</div>

<div class="descriptions">
<h1>Simplicity</h1> 
<p class="description">Simple deployment using Helm charts and schema-bound Kubernets custom resouces with a declarative configuration.</p> 

<h1>Scalability</h1>
<p class="description">All services are designed to be horizontally scalable and can be easily deployed in a Kubernetes cluster.</p>

<h1>Cloud-native</h1>
<p class="description">Managed by schema-based Kubernetes custom resources and Helm charts for easy integration with any cloud-native configuration management tool.</p>

<h1>Cost efficiency</h1>
<p class="description">Price efficiency is a key factor the services design. They can be used with any cloud provider with on-demand and spot instances.</p>
</div>

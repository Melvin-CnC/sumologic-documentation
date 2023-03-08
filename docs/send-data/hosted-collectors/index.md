---
slug: /send-data/hosted-collectors
title: Hosted Collectors
description: Hosted Collectors allow you to upload data stored in the cloud to Sumo Logic. You can configure Sources for Collectors that are hosted in Amazon Web Services (AWS), Microsoft, or other hosting services.
tags: [hosted collectors]
---

import DocCardList from '@theme/DocCardList';
import {useCurrentSidebarCategory} from '@docusaurus/theme-common';
import Iframe from 'react-iframe';

*Hosted Collectors* allow you to send data to Sumo Logic without deploying an agent. We host the Collector and its Sources on our end, in AWS — no need to install it on a local system in your deployment.

With a single Hosted Collector, you can create and configure Sources to collect data from any number of Sources, for example:

* Cloud-to-Cloud collection from AWS, Azure, Google Cloud Platform, and more SaaS tools
* Send data directly to Sumo endpoint using your custom collection method

Data collection flow for S3 buckets and HTTP requests:<br/>![team built hosted diagram.png](/img/send-data/team-built-hosted-diagram.png)

Just as Installed Collectors, you can monitor the activity of Hosted Collectors using the Status tab.

:::note
The maximum number of Collectors allowed per organization is 10,000.
:::

## Guides

In this section, we'll introduce the following concepts:

<div className="box-wrapper" markdown="1">
<div className="box smallbox1 card">
  <div className="container">
  <img src={useBaseUrl('img/send-data/.png')} alt="Thumbnail icon" width="45"/>
  <h4><a href="/docs/send-data/hosted-collectors/configure-hosted-collector">Configrure a Hosted Collector and Source</a></h4>
  <p>Set up Hosted Collectors so you can move data from an Amazon S3 bucket or HTTP Source to Sumo Logic.</p>
  </div>
</div>
<div className="box smallbox2 card">
  <div className="container">
  <img src={useBaseUrl('img/send-data/.png')} alt="Thumbnail icon" width="45"/>
  <h4><a href="/docs/send-data/hosted-collectors/amazon-aws">Amazon/AWS Sources</a></h4>
  <p>Sumo Logic offers hosted Sources to collect from many AWS products.</p>
  </div>
</div>
    <div className="box smallbox3 card">
      <div className="container">
      <img src={useBaseUrl('img/send-data/.png')} alt="Thumbnail icon" width="45"/>
      <h4><a href="/docs/send-data/hosted-collectors/cloud-to-cloud-integration-framework">Cloud-to-sCloud Integration Framework Sources</a></h4>
      <p>The Cloud-to-Cloud Integration Framework is a fully-managed collection system that collects logs and events directly from SaaS and Cloud platforms.</p>
      </div>
    </div>
    <div className="box smallbox4 card">
      <div className="container">
      <img src={useBaseUrl('img/send-data/.png')} alt="Thumbnail icon" width="45"/>
      <h4><a href="/docs/send-data/hosted-collectors/google-source">Google Sources</a></h4>
      <p>Sumo Logic offers hosted Sources to collect from these Google products.</p>
      </div>
    </div>
    <div className="box smallbox5 card">
      <div className="container">
      <img src={useBaseUrl('img/send-data/.png')} alt="Thumbnail icon" width="45"/>
      <h4><a href="/docs/send-data/hosted-collectors/ms-office-audit-source">Microsoft Sources</a></h4>
      <p>Configure Sumo Logic to collect logs for the following Audit Log content types to track and monitor usage of Microsoft Office 365.</p>
      </div>
    </div>
    <div className="box smallbox6 card">
      <div className="container">
      <img src={useBaseUrl('img/send-data/.png')} alt="Thumbnail icon" width="45"/>
      <h4><a href="/docs/send-data/hosted-collectors/cloud-syslog-source">Cloud Syslog Sources</a></h4>
      <p>You can configure a cloud syslog source to allow a syslog client to send RFC 5424-compliant messages to Sumo.</p>
      </div>
    </div>
    <div className="box smallbox7 card">
      <div className="container">
      <img src={useBaseUrl('img/send-data/.png')} alt="Thumbnail icon" width="45"/>
      <h4><a href="/docs/send-data/hosted-collectors/http-source">HTTP Sources for Logs, Metrics, Traces, OLTP</a></h4>
      <p>An HTTP Source is an endpoint for receiving logs, metrics, traces, and OTLP data uploaded to a unique URL generated for the Source.</p>
      </div>
    </div>
    </div>

## Micro Lesson: Hosted Collector Overview

<Iframe url="https://www.youtube.com/embed/bjbTm3vR2nA"
        width="854px"
        height="480px"
        id="myId"
        className="video-container"
        display="initial"
        position="relative"
        allow="accelerometer; autoplay=1; clipboard-write; encrypted-media; gyroscope; picture-in-picture"
        allowfullscreen
        />

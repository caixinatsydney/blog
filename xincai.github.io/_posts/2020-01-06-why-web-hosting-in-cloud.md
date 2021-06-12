---
date: 2020-01-06
title: Web Application Hosting in the Cloud Using AWS
categories:
  - cloud
author_staff_member: james
---
The first question that you should ask concerns the value of moving a classic web application hosting solution into the AWS Cloud. If you decide that the cloud is right for you, you’ll need a suitable architecture. This section helps you evaluate an AWS Cloud solution. It compares deploying your web application in the cloud to an on-premises deployment, presents an AWS Cloud architecture for hosting your application, and discusses the key components of this solution.

![Cat](https://source.unsplash.com/random/1500x1146)

How AWS Can Solve Common Web Application Hosting Issues

## A Cost-Effective Alternative to Oversized Fleets Needed to Handle Peaks

If you’re responsible for running a web application, you face a variety of infrastructure and architectural issues for which AWS can provide seamless and cost-effective solutions. The following are just some of the benefits of using AWS over a traditional hosting model.

![apricot](https://source.unsplash.com/random/1500x1147)

In the traditional hosting model, you have to provision servers to handle peak capacity. Unused cycles are wasted outside of peak periods. Web applications hosted by AWS can leverage on-demand provisioning of additional servers, so you can constantly
adjust capacity and costs to actual traffic patterns. For example, the following graph shows a web application with a usage peak from 9AM to 3PM and less usage for the remainder of the day. An automatic scaling approach based on actual traffic trends, which provisions resources only when needed, would result in less wasted capacity and a greater than 50 percent reduction in cost.

## A Scalable Solution to Handling Unexpected Traffic Peaks

An even more dire consequence of the slow provisioning associated with a traditional hosting model is the inability to respond in time to unexpected traffic spikes. There are many stories about web applications going down because of an unexpected spike in traffic after the site is mentioned in the popular media. The same on-demand capability that helps web applications scale to match regular traffic spikes can also handle an unexpected load. New hosts can be launched and ready in a matter of minutes, and they can be taken offline just as quickly when traffic returns to normal.

![Marketing](https://source.unsplash.com/random/1500x1148)

## An On-Demand Solution for Test, Load, Beta, and Preproduction Environments

The hardware costs of building out a traditional hosting environment for a production web application don’t stop with the production fleet. Quite often, you need to create preproduction, beta, and testing fleets to ensure the quality of the web application at each stage of the development lifecycle. While you can make various optimizations to ensure the highest possible use of this testing hardware, these parallel fleets are not always used optimally: a lot of expensive hardware sits unused for long periods of time. 

![Lady bugs](https://source.unsplash.com/random/1500x1149)

In the AWS Cloud, you can provision testing fleets as you need them. Additionally, you can simulate user traffic on the AWS Cloud during load testing. You can also use these parallel fleets as a staging environment for a new production release. This enables quick switchover from current production to a new application version with little or no service outages.

[source](https://aws.amazon.com/): AWS

<iframe style="width:120px;height:240px;" marginwidth="0" marginheight="0" scrolling="no" frameborder="0" src="//ws-na.amazon-adsystem.com/widgets/q?ServiceVersion=20070822&OneJS=1&Operation=GetAdHtml&MarketPlace=US&source=ac&ref=tf_til&ad_type=product_link&tracking_id=1688800-20&marketplace=amazon&region=US&placement=B07ZPC9QD4&asins=B07ZPC9QD4&linkId=64d15f49d4838283b5edc2fc600f687f&show_border=false&link_opens_in_new_window=false&price_color=333333&title_color=0066c0&bg_color=ffffff"></iframe>

<iframe style="width:120px;height:240px;" marginwidth="0" marginheight="0" scrolling="no" frameborder="0" src="//ws-na.amazon-adsystem.com/widgets/q?ServiceVersion=20070822&OneJS=1&Operation=GetAdHtml&MarketPlace=US&source=ac&ref=tf_til&ad_type=product_link&tracking_id=1688800-20&marketplace=amazon&region=US&placement=B07L32B9C2&asins=B07L32B9C2&linkId=54c170cca8a3ef001ae2a865ee4640c6&show_border=false&link_opens_in_new_window=false&price_color=333333&title_color=0066c0&bg_color=ffffff"></iframe>

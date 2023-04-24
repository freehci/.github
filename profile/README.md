# FreeHCI

## Preface

There is a significant lack of low-threshold solutions for HCI. Several alternatives exist, but they often come at a price that doesn't fit into the tight budgets of companies lacking the necessary financial resources and IT expertise. The FreeHCI project was started in response to existing solutions such as Dell EMC VxRail, Nutanix, and HPE Simplivity. The project aims to address the problems and challenges associated with today's market leaders and become a visible contender that challenges established players, demonstrating how new technology, fresh ideas, and a forward-thinking open-source community can provide customers with a better experience. Please note that this is an work in progress project. No mechanisms for deploying and maintaining your environment is implemented yet. We will let you know when you can download a working version, so you can explore the new functionality and experience the possibilities the product offers.

## Technology

We are strong proponents of openness in how things are built. Openness about potential issues that may arise and how they are resolved. We want to listen to what customers and the community have to say. We may not be world champions, but we do our best to improve continuously. The world is tired of black boxes that promise to solve all problems at a sky-high price, while in reality, suppliers can hide technical debt and poor design behind closed systems. We don't need magical soup in black boxes - we need something that works and can at least be fixed if something breaks. We need something well-documented and widely understood.

## Goals

Our goal is to enable users to set up hyper-converged infrastructure (HCI) without prior knowledge of how to do so. FreeHCI leverages existing technologies to keep hardware up-to-date and will inform you of the supported technologies for your hardware. For vSphere, we rely on VMware's own HCL lists.

## Getting Started

Add servers either through the vendor's management system, such as Dell Open Manage Enterprise, HPE OneView, or Lenovo XClarity, or add servers directly using the server's OOB management card. FreeHCI supports IPMI, Redfish, and SSH.

Once you have added the servers you want to use for your HCI, you will have the option to deploy the operating system of your choice, whether it's VMware vSphere, Microsoft Hyper-V, or Red Hat oVirt. Our goal is to gain as broad support for other hardware vendors as possible. We will allow hardware vendors to re-brand FreeHCI so they can put their own stamp on the product.

## Who Are We?

- freehci.org: The Project
- freehci.com: The Company and the Product

Both the project and the company are marketed under the same name. We cannot rule out that the company and the product will be subject to changes, both in terms of organization and name, but the project will remain open-source and accessible to the public.

## Screenshots

![Image description](https://github.com/freehci/freehci-appliance/blob/main/screenshots/rack-view-server-view.png?raw=true)

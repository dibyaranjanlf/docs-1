## What is EasyCLA?

_EasyCLA_ helps maintainers of open source projects streamline their workflows and reduce the hassle of managing Contributor License Agreements \(CLAs\) and authorizing contributors. By automating many of the manual processes, this open source solution hosted by the Linux Foundation reduces delays for developers to get authorized under a CLA.

## What is a CLA?

A _Contributor License Agreement_ \(CLA\) defines the terms under which intellectual property is contributed to a company or project. Typically, the intellectual property is software under an open source license. EasyCLA helps to ensure that contributions are not pulled into a project unless a CLA covering the contributor has been signed. CLAs typically fall into one of two categories:
* **Corporate Contributor License Agreement**

  If the company \(employer\) owns the contribution, a CCLA signatory signs a Corporate CLA. The Corporate CLA legally binds the corporation, so the agreement must be signed by a person with authority to enter into legal contracts on behalf of the corporation. A Corporate CLA may not remove the need for every employee \(developer\) to sign their own Individual CLA -- which separately covers contributions owned by the individual contributor -- if the project requires this.

* **Individual Contributor License Agreement**

  If as an individual you own the contribution, you sign the Individual CLA. A signed Individual CLA may be required before an individual's contribution can be merged into the project repository.

## How Does it Work?

This high-level diagram shows the different flows and roles that EasyCLA supports:

![CLA Diagram](../.gitbook/assets/cla_diagram_v8.png)

# EasyCLA Requirements

**Important:** Before you get started, make sure your project meets the EasyCLA requirements:

EasyCLA has the following requirements:

* \(Gerrit only\) Your project is hosted on the Linux Foundation platform
* Your project repositories are in GitHub or Gerrit
* You have a Linux Foundation identification and credentials. If you do not have a Linux Foundation identification \(LF ID\), go to [https://identity.linuxfoundation.org](https://identity.linuxfoundation.org) and complete the form to sign up.
* For Corporate CLAs, your company has a corporate authority role

As a repository administrator, enable Branch Restrictions and Branch Protection for your organizations in GitHub. Set the restrictions and protection to enable required status checks on a branch regardless of the role for the organization.

## What Role are You?

How you interact with EasyCLA depends on your role. EasyCLA supports the following roles in its workflow:

### Project Manager

You are a _project manager_ if you are the project maintainer who has responsibilities such as managing a project’s GitHub organization or Gerrit instance, members, repositories, and CLAs.

As the Project Manager, following are the pre-requisites to get access to EasyCLA:

1. If you do not have a Linux Foundation identification and credentials, go to https://identity.linuxfoundation.org and complete the form to sign up.
1. Share your sign-up username with the CLA administration team at docucla@linuxfoundation.org.
1. Provide sample ICLA and CCLA template documents to the CLA administration team at docucla@linuxfoundation.org.
1. After the CLA administration team confirms your setup, you can Sign In to the CLA Management Console to do the EasyCLA activities for Project Managers.

Fill out this form to provide information : [Pre-requisite form for Project Manager ](https://forms.gle/RuUgDKVg6m6Lj7LBA)

With EasyCLA, you do the following CLA set-up tasks:

1. [Install the EasyCLA Application](install-the-easycla-application.md).
2. [Add a CLA Group](add-a-cla-group.md).
3. [Add Contributor License Agreements](https://github.com/communitybridge/easycla/tree/9d90365534e45b86032affe9fbdcaab3f4cd16a2/docs/add-contributor-license-agreements/README.md).
4. Add [GitHub repositories](add-github-repositories-to-cla-monitoring-or-remove-them-from-cla-monitoring.md) or [Gerrit instances](add-gerrit-instances-to-cla-monitoring-or-delete-them-from-cla-monitoring.md) to enforce CLA monitoring.

At any time, you can change the settings to manage your project CLA monitoring, and do other management tasks:

* [View Current and Previous CLA PDFs](view-current-and-previous-cla-pdfs.md)
* [Manage CLA Group Details](manage-cla-group-details.md)

### Contributor

You are a _contributor_ \(developer\) if you contribute code to GitHub or Gerrit projects. With EasyCLA, you will follow different workflows depending on whether the project is hosted on GitHub or Gerrit, and whether you contribute on behalf of a company or yourself as an individual:

* **GitHub company** contributor: [confirm your association with a company](contribute-to-a-github-company-project.md) that has a signed Corporate Contributor License Agreement.
* **GitHub individual** contributor: [sign an Individual Contributor License Agreement](sign-a-cla-as-an-individual-contributor-to-github.md).
* **Gerrit company** contributor: [confirm your association with a company](contribute-to-a-gerrit-project.md) that has a signed Corporate Contributor License Agreement.
* **Gerrit individual** contributor: [sign an Individual Contributor License Agreement](contribute-to-a-gerrit-project.md).

### Corporate CLA Manager

You are a _Corporate CLA manager_ \(CCLA manager\) if you are the person authorized to manage the list of approved contributors under your company’s Corporate CLA.

1. As the CLA Manager or the CLA signatory, following are the pre-requisites for the CLA tasks after you Sign In to the CLA Corporate Console:

1. CLA manager: Add a Company to a Project.
1. CLA signatory: Sign a Corporate CLA on behalf of the company and Review and Sign a Corporate CLA by Request—this signatory has legal authority to sign documents on behalf of the company.

1. CLA manager: Whitelist Contributors—each whitelist applies to the project for which the company has signed a Corporate CLA.

With this responsibility, you use EasyCLA to:

* [Add companies to a project](add-a-company-to-a-project.md).
* [Whitelist contributors](whitelist-contributors.md).

### Corporate CLA Signatory

You are a _Corporate CLA signatory_ \(CCLA signatory\) if you are authorized to sign contracts, such as the project’s CLA, on behalf of the company. With EasyCLA, you can:

* [Sign a Corporate CLA on behalf of the company](sign-a-corporate-cla-on-behalf-of-the-company.md)—as a signatory you need to have legal authority to sign documents on behalf of the company.
* [Review and sign a Corporate CLA by request](review-and-sign-a-corporate-cla-by-request.md).


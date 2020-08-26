# Add or Remove GitHub Repositories from CLA Monitoring

As a project manager, you can add GitHub repositories to CLA monitoring or remove them from CLA monitoring. Before you can add or manage GitHub repositories, you must [add/connect](./#to-add-github-organization) the GitHub organization. You have already connected the GitHub organization during setting up IT services, the GitHub organization with the configured repositories shows under the GitHub tab.

**Do these steps:**

1. [Sign in](../sign-in-to-project-console.md).

2.Click a **project** of interest.  
The project page appears.

3. Navigate to **Product Services** tab, and click **CLA**.

![](../../../../.gitbook/assets/cla-product-services.png)

3. For a project under a project group, click **Add/Manage Repos**. 

![Add and Manage Repositories](../../../../.gitbook/assets/add-manage-repositories.png)

4. In the **GITHUB** repositories pane, click **CONFIGURE GITHUB REPOSITORIES**.

The Configure GitHub Repositories dialog appears and lists the GitHub repositories that are available for your organization.

![CLA Configure GitHub Repositories](../../../../.gitbook/assets/cla-configure-github-repositories.png)

4. For the repository that you want to configure, click an option:

* **ADD** adds the repository to the CLA group and to CLA monitoring. After you add a repository, the REMOVE option becomes available next to the repository.
* **REMOVE** disables CLA enforcement on the repository. After you remove a repository, the ADD option appears next to the repository.
* **REMOVE** removes the repository from the CLA group and CLA monitoring. After you remove a repository, the ADD option appears next to the repository.
* **DISABLED** indicates that the repository has been configured for another CLA group and thus cannot be configured for the selected CLA group.
* **ADD ALL REPOS** adds all repositories for the corresponding GitHub Organization to CLA enforcement. After you add the repositories the REMOVE option appears next to each repository.

5. Click **CLOSE**.

The CLA Management Console appears. Repositories shows a checkmark next to each repository that EasyCLA will monitor for the organization and the CLA group.

![CLA GitHub Repositories](../../../../.gitbook/assets/cla-github-repositories.png)

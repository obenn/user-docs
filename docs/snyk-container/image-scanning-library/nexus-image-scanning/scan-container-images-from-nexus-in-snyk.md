# Scan container images from Nexus in Snyk

Snyk tests and monitors your Nexus container images by evaluating its tags in your repositories. Once imported to Snyk, your image vulnerabilities are surfaced and can be triaged easily.

To add images from Nexus to Snyk:

**Prerequisites**:

* Have a Snyk account with access to the relevant organization \(given by an administrator\).
* Nexus integration configured. To learn more about that, follow the steps in [Container security with Nexus integration](https://support.snyk.io/hc/en-us/articles/4403626400145)

**Steps:**

1. Log in to your account and navigate to the relevant group and organization that you want to manage.![AddProjectMenu.gif](https://support.snyk.io/hc/article_attachments/360007147238/uuid-da316a4a-c823-cf03-f37f-5305446dc970-en.gif)
2. Under the **Projects** tab, click **Add project**. The list of integrations already configured on your account opens. Select the **Nexus** option or **Other** if Nexus doesn’t appear.
3. The **Which images do you want to test?** view appears, displaying all of the available images for your connected registry, grouped by each of your repositories, similar to the following: ![mceclip0.png](https://support.snyk.io/hc/article_attachments/360017894918/mceclip0.png) 
4. Select single or multiple images to be imported to Snyk. Selection can be done by choosing a specific image or selecting an entire repository. You can also search by image name to find specific images to import. To finish, click **Add selected repositories** on the top-right. 
5. A status bar appears at the top of the page as the images are imported; you can continue working in the meantime.
6. When the import ends:
   * You can view the newly imported image in the **Projects** page \(marked with a **NEW** tag\). Images are grouped by repository and are each linked individually to a detailed **Project** page.
     * An **import log** becomes available and can be reached at the top of the projects list. 
   * To enrich the data and get recommendations regarding your base image, you can connect your Dockerfile to the image project, under **Settings**. For more info, see [Adding your Dockerfile and test your base image](https://support.snyk.io/hc/articles/360003916218#UUID-9ab347a6-8af0-ef6c-5ebd-cec21fbfab29).

Nexus imports are indicated with a unique icon , and you can also filter to view only the Nexus projects:

![mceclip0.png](https://support.snyk.io/hc/article_attachments/4403626444945/mceclip0.png)

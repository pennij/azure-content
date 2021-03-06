<properties linkid="develop-dotnet-website-from-gallery" urlDisplayName="Web Site from Gallery" pageTitle=".NET web site from Gallery - Windows Azure tutorial" metaKeywords="Azure build website, manage website Azure" metaDescription="A tutorial that teaches you how to create a new web site in Windows Azure. Also learn how to launch and manage your site using the Management Portal." metaCanonical="" disqusComments="1" umbracoNaviHide="1" />


<div chunk="../chunks/article-left-menu.md" />

# Create an Orchard CMS web site from the gallery in Windows Azure

The gallery makes available a wide range of popular web applications developed by Microsoft, third party companies, and open source software initiatives. Web applications created from the gallery do not require installation of any software other than the browser used to connect to the [Windows Azure Management Portal](http://manage.windowsazure.com). 

In this tutorial, you'll learn:

- How to create a new site from the gallery

- How to launch and manage your site from the Management Portal
 
You'll build an Orchard CMS site that uses a default template. [Orchard](http://www.orchardproject.net/) is a free, open-source, .NET-based CMS application that allows you to create customized, content-driven web sites. Orchard CMS includes an extensibility framework through which you can [download additional modules and themes](http://gallery.orchardproject.net/) to customize your site. The following illustration shows the Orchard CMS site that you will create.

![Orchard blog][13]

<div chunk="../../Shared/Chunks/create-account-and-websites-note.md" />

<h2><span class="short-header">Create web site from gallery</span>Create an Orchard web site from the gallery</h2>

1. Login to the [Windows Azure Management Portal](http://manage.windowsazure.com).

2. Click the **New** icon on the bottom left of the dashboard.
	
	![Create New][1]

3. Click the **Web Site** icon, and click **From Gallery**.
	
	![Create From Gallery][2]

1. Locate and click the Orchard CMS icon in list, and then click **Next**.
	
	![Orchard from list][3]

4. On the **Configure Your App** page, enter or select values for all fields:
	
- Enter a URL name of your choice.	
- Select the region closest to your users. (This will ensure best performance.)

	![configure your app][4]

5. Then click the **Complete** check box.

After you click **Complete** Windows Azure will initiate build and deploy operations. While the web site is being built and deployed the status of these operations is displayed at the bottom of the Web Sites page. After all operations are performed,  A final status message when the site has been successfully deployed.

<h2><span class="short-header">Launch and manage site</span>Launch and manage your Orchard site</h2>

1. Click the name of your new site on the **Web Sites** page to open the dashboard for the site.

	![launch dashboard][5]

2. On the dashboard, under **quick glance**, scroll down and click the link under **Site URL** to open the site's welcome page.

3. Enter appropriate configuration information required by Orchard, and then click **Finish Setup** to complete the configuration and open the web site’s home page.

	![login to Orchard][7]

	You'll have a new Orchard site that looks similar to the screenshot below.  

	![your Orchard site][13]

4. Follow the details in the [Orchard Documentation](http://docs.orchardproject.net/) to learn more about Orchard and configure your new site.

<h2><span class="short-header">Next steps</span>Next step</h2>
* [Develop and deploy a web site with Microsoft WebMatrix](/en-us/develop/net/tutorials/website-with-webmatrix) -- Learn how to edit a Windows Azure web site in WebMatrix. 
* [Deploying an ASP.NET web application to a Windows Azure web site and SQL Database](/en-us/develop/net/tutorials/web-site-with-sql-database/)-- Learn how to creatd a new web site from Visual Studio.

[1]: ../media/orchardgallery-01.png
[2]: ../media/orchardgallery-02.png
[3]: ../media/orchardgallery-03.png
[4]: ../media/orchardgallery-04.png
[5]: ../media/orchardgallery-05.png
[6]: ../media/orchardgallery-06.png
[7]: ../media/orchardgallery-07.png
[13]: ../media/orchardgallery-08.png
[http://www.windowsazure.com]: http://www.windowsazure.com
[0]: ../../devcenter/shared/media/freetrialonwindowsazurehomepage.png
[14]: ../../devcenter/shared/media/antares-iaas-preview-01.png
[15]: ../../devcenter/shared/media/antares-iaas-preview-05.png
[16]: ../../devcenter/shared/media/antares-iaas-preview-06.png
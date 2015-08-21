##GroupDocs.Viewer for Java – ezPublish Add-on

GroupDocs.Viewer for Java is multi-format, browser-agnostic [Java document viewer library](http://groupdocs.com/java/document-viewer-library) designed as a middleware for easy integration into any web-based application or website. With this add-on, ezPublish developers can easily integrate the viewer into their websites.

GroupDocs.Viewer for Java provides a web-based GUI that can be easily customized with your own CSS and embedded to a web-page as a document viewer widget. End users can then view documents via the widget without having to leave your website.

####With GroupDocs.Viewer for Java, you get:

- A truly universal document viewer that supports 50+ document formats, including PDF, Microsoft Word, Excel, PowerPoint, Outlook, Visio, CAD, multipage TIFF, etc.
- Cross-platform compatibility. End users can view documents on your website from any web-enabled device using any standard web-browser.
- Ease of deployment. There is no need to install anything on the client side. You only need to deploy GroupDocs.Viewer for Java on the server and integrate it into ezPublish using this add-on.
- Ability to securely share documents in a read-only mode. GroupDocs.Viewer for Java allows you to disable the print, download and text selection options, so that viewers can’t copy the documents you share on your website.   

___

###Add-on Installation:

Please note that this plugin integrates a downloadable Java version of GroupDocs.Viewer, which can be deployed on-premises. We also offer a downloadable [.NET version](https://github.com/groupdocs/ezpublish-groupdocs-viewer-dotnet) and a [cloud-based integration](https://github.com/groupdocs/ez-groupdocs-viewer).

Also, please be aware that GroupDocs.Viewer for Java is a commercial library, but you can test it with a free evaluation. 

1. Unzip the **groupdocsViewerNet** package to the **groupdocsViewer** folder within the **extensions** directory of your ezPublish site. 
2. Open the **site/settings/override/site.ini.append.php** file and add **ActiveExtensions[]=groupdocsViewerNet** under **[ExtensionSettings]**.
3. Go to: **Admin** > **Setup** > **Extensions** and check the **groupdocsViewer** checkbox.
4. Go to: **Setup** > **Extensions** and press the **Regenerate auto loaded arrays for extensions** in the bottom of the page.
5. Go to: **User Accounts** > **Roles and policies** > **Anonymous** then click **Edit Role**.
6. If **groupdocsViewerNet** is not listed there, press **New Policy** > choose **Module: groupdocsViewerNet** > **Grant access to all functions** > **Save**.
6. Go to **Setup** and press **Clear all caches**.

___

###Useful Links

GroupDocs.Viewer for Java Library - Product Home:    
[http://groupdocs.com/java/document-viewer-library](http://groupdocs.com/java/document-viewer-library)

GroupDocs.Viewer for Java on the ezPublish Marketplace:   
[http://projects.ez.no/groupdocs_viewer_for_java](http://projects.ez.no/groupdocs_viewer_for_java)

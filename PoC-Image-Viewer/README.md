# PoC Image Viewer

The Image Viewer proof of concept app demonstrates how a Canvas App can be used, with the help of a Cloud Flow, to show the latest image uploaded to a specific SharePoint document library.

I will admit that I built this solution several years back. However, it does demonstrate a few fundamental principles:

1. I use a 'naming conversation' for connection references and environment variables. In my case, I am prefixing the names with the solution's initials.
2. I apply a connection reference and environment variables to steps within the Cloud Flow.
3. The Canvas App calls a Flow to retrieve the last image created within a SharePoint library.

![Solution-Overview](https://github.com/sionjlewis/Power-Platform/blob/main/PoC-Image-Viewer/Assets/PoC-Image-Viewer-Solution-Overview.PNG)

The point here is less about the implementation and more about how we can make our solutions more manageable to read and coexist.

## Set-up

I have not included the scripts to recreate the document library. However, you can use the same library as the **Enhancing EXIF Data Handling in SharePoint Online: A Solution Guide** article. For more details, visit [www.sjlewis.com](https://www.sjlewis.com/2023/09/22/enhancing-exif-data-handling-in-sharepoint-online-a-solution-guide/).

## License

https://github.com/sionjlewis/Power-Platform/blob/main/LICENSE

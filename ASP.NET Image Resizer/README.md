# ASP.NET Image Resizer
## Requires
- Visual Studio 2015
## License
- MIT
## Technologies
- ASP.NET
## Topics
- asp.net image resizer
## Updated
- 08/06/2019
## Description

<h1>ImageUltimate: ASP.NET Image Resizer</h1>
<p>ImageUltimate is the fastest and easiest ASP.NET Image Resizer which supports both ASP.NET MVC and ASP.NET WebForms web applications/web sites. ImageUltimate can also be used with .NET desktop applications for manipulating several image formats.&nbsp;<span>Let
 your web site prepare images automagically for you. Save images once and embrace the responsive web.</span></p>
<ul>
<li>Chain image manipulation commands to get variations in the brink of an eye. </li></ul>
<ul>
<li>Keep your source images in their original formats (eg. Psd, Raw) and serve the resulting images in any web format.
</li></ul>
<ul>
<li>Have SEO friendly urls for your images to improve your rankings. </li></ul>
<ul>
<li>Vastly reduce your outgoing bandwidth usage with the help of smart versioning.
</li></ul>
<p><img id="159613" src="https://i1.code.msdn.s-msft.com/aspnet-image-resizer-b1c8f3d0/image/file/159613/1/imageultimate-screenshot.png" alt="" width="736"></p>
<p><strong>Note:</strong> This project&nbsp;contains a fully working version of the product, however without a license key it will run in trial mode. For more information, please see&nbsp;<a href="http://www.gleamtech.com/imageultimate">ImageUltimate: ASP.NET
 Image Resizer</a>&nbsp;product page.</p>
<p>&nbsp;</p>
<h3>Features:</h3>
<ul>
<li>
<p>Can load and save many image file formats (raster, vector and camera raw).</p>
</li><li>
<p>Provides a fluent interface for easily chaining image manipulation commands.</p>
</li><li>
<p>Vastly faster (10x) than <a class="libraryLink" href="https://msdn.microsoft.com/en-US/library/System.Drawing.aspx" target="_blank" title="Auto generated link to System.Drawing">System.Drawing</a> namespace and optimized specifically for web use. Minimal memory usage and the ability to process very large images in a fast manner.</p>
</li><li>
<p>Provides detailed information about an image file like format, size, DPI, pixel format and metadata like EXIF and IPTC.</p>
</li><li>
<p>Fast thumbnail generation, smartly looks for a EXIF thumbnail, removes black stripes above and below it and resizes it down further if needed.</p>
</li><li>
<p>Provides these image transforms: Resize, LiquidResize (seam carving), Crop, TrimBorders, Rotate, Flip.</p>
</li><li>
<p>Provides these image color/tone corrections and filters: Brightness, Contrast, Enhance, Blur, Sharpen.</p>
</li><li>
<p>Caches generated images both on server and browser with a smart versioning algorithm. A unique and browser-cacheable url is generated according to the chained commands and whenever you change these commands (or modify the source image externally), the url
 will vary and this will cause browser to automatically detect changes (no need to press F5).</p>
</li><li>
<p>Generates SEO friendly urls. By default the file name of the source image is used but it's possible to override this file name for SEO purposes.</p>
</li><li>
<p>Single managed DLL (works both on 32-bit and 64-bit) for easy deployment and no dependencies. No messy Web.config settings. Just drop it in your bin folder and you are ready to go.</p>
</li><li>
<p>Strongly-typed API for web, no need to learn and memorize messy url querystring parameters, just chain commands with the help of intellisense.</p>
</li></ul>
<div>
<h3 style="margin-top:24px; margin-bottom:16px; font-size:1.25em; font-weight:600; line-height:1.25; color:#24292e">
</h3>
<h3>Supported Formats:</h3>
<table>
<thead>
<tr>
<th align="left">Format</th>
<th align="left">Extensions</th>
<th align="left">Load</th>
<th align="left">Save</th>
</tr>
</thead>
<tbody>
<tr>
<th colspan="5" align="left">Raster Image Formats:</th>
</tr>
<tr>
<td>Joint Photographic Experts Group (JPEG)</td>
<td>.jpg, .jpeg, .jpe, .jif, .jfif, .jfi, .exif</td>
<td>✓</td>
<td>✓</td>
</tr>
<tr>
<td>JPEG 2000 (JP2)</td>
<td>.jp2, .jpf, .jpx, .j2k, .j2c, .jpc</td>
<td>✓</td>
<td>✓</td>
</tr>
<tr>
<td>Portable Network Graphics (PNG)</td>
<td>.png</td>
<td>✓</td>
<td>✓</td>
</tr>
<tr>
<td>Graphics Interchange Format (GIF)</td>
<td>.gif</td>
<td>✓</td>
<td>✓</td>
</tr>
<tr>
<td>WebP Image</td>
<td>.webp</td>
<td>✓</td>
<td>✓</td>
</tr>
<tr>
<td>Bitmap Picture (BMP)</td>
<td>.bmp</td>
<td>✓</td>
<td>✓</td>
</tr>
<tr>
<td>Windows Metafile (WMF)</td>
<td>.wmf</td>
<td>✓</td>
<td>&nbsp;</td>
</tr>
<tr>
<td>Device Independent Bitmap (DIB)</td>
<td>.dib</td>
<td>✓</td>
<td>✓</td>
</tr>
<tr>
<td>Windows Icon (ICO)</td>
<td>.ico</td>
<td>✓</td>
<td>✓</td>
</tr>
<tr>
<td>Truevision Graphics Adapter (TARGA)</td>
<td>.tga</td>
<td>✓</td>
<td>✓</td>
</tr>
<tr>
<td>Adobe Photoshop Document (PSD)</td>
<td>.psd, .psb</td>
<td>✓</td>
<td>✓</td>
</tr>
<tr>
<th colspan="5" align="left">Scanner Image Formats:</th>
</tr>
<tr>
<td>Tagged Image File Format (TIFF)</td>
<td>.tif, .tiff, .tff</td>
<td>✓</td>
<td>✓</td>
</tr>
<tr>
<th colspan="5" align="left">Vector Image Formats:</th>
</tr>
<tr>
<td>Scalable Vector Graphics (SVG)</td>
<td>.svg</td>
<td>✓</td>
<td>✓</td>
</tr>
<tr>
<td>Windows Enhanced Metafile (EMF)</td>
<td>.emf</td>
<td>✓</td>
<td>&nbsp;</td>
</tr>
<tr>
<th colspan="5" align="left">Camera Image Formats:</th>
</tr>
<tr>
<td>Adobe Digital Negative (Leica)</td>
<td>.dng</td>
<td>✓</td>
<td>&nbsp;</td>
</tr>
<tr>
<td>Sony Alpha Raw Image Format</td>
<td>.arw</td>
<td>✓</td>
<td>&nbsp;</td>
</tr>
<tr>
<td>Sony Raw Format</td>
<td>.sr2, .srf</td>
<td>✓</td>
<td>&nbsp;</td>
</tr>
<tr>
<td>Canon Digital Camera Raw Image Format</td>
<td>.cr2, .crw</td>
<td>✓</td>
<td>&nbsp;</td>
</tr>
<tr>
<td>Nikon Digital SLR Camera Raw Image File</td>
<td>.nef, .nrw</td>
<td>✓</td>
<td>&nbsp;</td>
</tr>
<tr>
<td>Fuji CCD-RAW Graphic File</td>
<td>.raf</td>
<td>✓</td>
<td>&nbsp;</td>
</tr>
<tr>
<td>Olympus Digital Camera Raw Image File</td>
<td>.orf</td>
<td>✓</td>
<td>&nbsp;</td>
</tr>
<tr>
<td>Pentax Electronic File</td>
<td>.pef</td>
<td>✓</td>
<td>&nbsp;</td>
</tr>
<tr>
<td>Kodak Digital Camera Raw Image Format</td>
<td>.kdc</td>
<td>✓</td>
<td>&nbsp;</td>
</tr>
<tr>
<td>Kodak Digital Camera Raw Image Format</td>
<td>.dcr</td>
<td>✓</td>
<td>&nbsp;</td>
</tr>
<tr>
<td>Minolta/Konica Minolta Raw Image File</td>
<td>.mrw</td>
<td>✓</td>
<td>&nbsp;</td>
</tr>
<tr>
<td>Epson RAW Format</td>
<td>.erf</td>
<td>✓</td>
<td>&nbsp;</td>
</tr>
<tr>
<td>Panasonic Lumix Raw Image</td>
<td>.rw2</td>
<td>✓</td>
<td>&nbsp;</td>
</tr>
<tr>
<td>Samsung Raw Format</td>
<td>.srw</td>
<td>✓</td>
<td>&nbsp;</td>
</tr>
<tr>
<td>Sigma Camera RAW Picture File</td>
<td>.x3f</td>
<td>✓</td>
<td>&nbsp;</td>
</tr>
<tr>
<td>Mamiya Raw Image File</td>
<td>.mef</td>
<td>✓</td>
<td>&nbsp;</td>
</tr>
<tr>
<td>Camera Raw Image File</td>
<td>.raw</td>
<td>✓</td>
<td>&nbsp;</td>
</tr>
<tr>
<th colspan="5" align="left">Totals:</th>
</tr>
<tr>
<td>31</td>
<td>48</td>
<td>31</td>
<td>12</td>
</tr>
</tbody>
</table>
<h3 style="margin-top:24px; margin-bottom:16px; font-size:1.25em; font-weight:600; line-height:1.25; color:#24292e">
</h3>
<h3 style="margin-top:24px; margin-bottom:16px; font-size:1.25em; font-weight:600; line-height:1.25; color:#24292e">
To use ImageUltimate in an ASP.NET MVC Project, do the following in Visual Studio:</h3>
<ol style="padding-left:2em; margin-top:0px; margin-bottom:16px; color:#24292e; font-size:16px">
<li>
<p style="margin-top:16px; margin-bottom:16px">Add references to ImageUltimate assemblies. There are two ways to perform this:</p>
<ul style="padding-left:2em; margin-top:0px; margin-bottom:0px">
<li>
<p style="margin-top:16px; margin-bottom:16px">Add reference to&nbsp;<span style="font-weight:600">GleamTech.Core.dll</span>&nbsp;and&nbsp;<span style="font-weight:600">GleamTech.ImageUltimate.dll</span>&nbsp;found in &quot;Bin&quot; folder of ImageUltimate-vX.X.X.X.zip
 package which you already downloaded and extracted.</p>
</li><li style="margin-top:0.25em">
<p style="margin-top:16px; margin-bottom:16px">Or install NuGet package and add references automatically via NuGet Package Manager in Visual Studio: Go to&nbsp;<span style="font-weight:600">Tools -&gt; NuGet Package Manager -&gt; Package Manager Console</span>&nbsp;and
 run this command:</p>
<p style="margin-top:16px; margin-bottom:16px"><code style="font-family:SFMono-Regular,Consolas,&quot;Liberation Mono&quot;,Menlo,Courier,monospace; font-size:13.6px; padding:0.2em 0.4em; margin:0px">Install-Package ImageUltimate -Source https://get.gleamtech.com/nuget/default/</code></p>
<p style="margin-top:16px; margin-bottom:16px">If you prefer using the user interface when working with NuGet, you can also install the package this way:</p>
<ul style="padding-left:2em; margin-top:0px; margin-bottom:0px">
<li>
<p style="margin-top:16px; margin-bottom:16px">&nbsp;GleamTech has its own NuGet feed so first you need to add this feed to be able to find GleamTech's packages. Go to&nbsp;<span style="font-weight:600">Tools -&gt; NuGet Package Manager -&gt; Package Manager
 Settings</span>&nbsp;and then click the&nbsp;<span style="font-weight:600">&#43;</span>&nbsp;button to add a new package source. Enter&nbsp;<code style="font-family:SFMono-Regular,Consolas,&quot;Liberation Mono&quot;,Menlo,Courier,monospace; font-size:13.6px; padding:0.2em 0.4em; margin:0px">GleamTech</code>&nbsp;in&nbsp;<span style="font-weight:600">Name</span>&nbsp;field
 and&nbsp;<code style="font-family:SFMono-Regular,Consolas,&quot;Liberation Mono&quot;,Menlo,Courier,monospace; font-size:13.6px; padding:0.2em 0.4em; margin:0px">https://get.gleamtech.com/nuget/default/</code>&nbsp;in&nbsp;<span style="font-weight:600">Source</span>field
 and click&nbsp;<span style="font-weight:600">OK</span>.</p>
</li><li style="margin-top:0.25em">
<p style="margin-top:16px; margin-bottom:16px">Go to&nbsp;<span style="font-weight:600">Tools -&gt; NuGet Package Manager -&gt; Manage NuGet Packages for Solution</span>, select&nbsp;<code style="font-family:SFMono-Regular,Consolas,&quot;Liberation Mono&quot;,Menlo,Courier,monospace; font-size:13.6px; padding:0.2em 0.4em; margin:0px">GleamTech</code>&nbsp;or&nbsp;<code style="font-family:SFMono-Regular,Consolas,&quot;Liberation Mono&quot;,Menlo,Courier,monospace; font-size:13.6px; padding:0.2em 0.4em; margin:0px">All</code>&nbsp;in
 the Package source dropdown on the top right. Now enter&nbsp;<code style="font-family:SFMono-Regular,Consolas,&quot;Liberation Mono&quot;,Menlo,Courier,monospace; font-size:13.6px; padding:0.2em 0.4em; margin:0px">ImageUltimate</code>&nbsp;in the search field, and click&nbsp;<span style="font-weight:600">Install</span>button
 on the found package.</p>
</li></ul>
</li></ul>
</li><li style="margin-top:0.25em">
<p style="margin-top:16px; margin-bottom:16px">Set ImageUltimate's global configuration. For example, you may want to set the license key and the default path for finding source images (SourcePath). Insert some of the following lines (if overriding a default
 value is required) into the&nbsp;<code style="font-family:SFMono-Regular,Consolas,&quot;Liberation Mono&quot;,Menlo,Courier,monospace; font-size:13.6px; padding:0.2em 0.4em; margin:0px">Application_Start</code>&nbsp;method of your&nbsp;<span style="font-weight:600">Global.asax.cs</span>:</p>
<div class="highlight highlight-source-cs" style="margin-bottom:16px">
<pre style="font-family:SFMono-Regular,Consolas,&quot;Liberation Mono&quot;,Menlo,Courier,monospace; font-size:13.6px; margin-top:0px; margin-bottom:0px; word-wrap:normal; padding:16px; overflow:auto; line-height:1.45; background-color:#f6f8fa; word-break:normal"><span class="pl-c" style="color:#6a737d">//Set this property only if you have a valid license key, otherwise do not</span>
<span class="pl-c" style="color:#6a737d">//set it so ImageUltimate runs in trial mode.</span>
<span class="pl-en" style="color:#6f42c1">ImageUltimateConfiguration.Current.LicenseKey</span> = &quot;QQJDJLJP34...&quot;;

<span class="pl-c" style="color:#6a737d">//The default SourcePath value is &quot;~/App_Data/ImageSource&quot;</span>
<span class="pl-c" style="color:#6a737d">//Both virtual and physical paths are allowed.</span>
<span class="pl-c" style="color:#6a737d">//Note that using a path under &quot;~/App_Data&quot; can have a benefit,</span>
<span class="pl-c" style="color:#6a737d">//for instance if you want to protect your original source files, i.e.</span>
<span class="pl-c" style="color:#6a737d">//prevent them from being downloaded directly, you can use this special </span>
<span class="pl-c" style="color:#6a737d">//folder which is restricted by ASP.NET runtime by default.</span>
<span class="pl-en" style="color:#6f42c1">ImageUltimateWebConfiguration.Current.SourcePath</span> = &quot;~/Content&quot;;

<span class="pl-c" style="color:#6a737d">//The default CacheLocation value is &quot;~/App_Data/ImageCache&quot;</span>
<span class="pl-c" style="color:#6a737d">//Both virtual and physical paths are allowed (or a Location instance for one of the supported </span>
<span class="pl-c" style="color:#6a737d">//file systems like Amazon S3 and Azure Blob).</span>
<span class="pl-c" style="color:#6a737d">//However it's recommended that you use a path inside your application folder </span>
<span class="pl-c" style="color:#6a737d">//(e.g. &quot;~/SomeFolder&quot;, &quot;/SomeFolder&quot; or &quot;C:\inetpub\wwwroot\MySite\SomeFolder&quot;)</span>
<span class="pl-c" style="color:#6a737d">//so that ImageUltimate can use RewritePath to pass download requests directly</span>
<span class="pl-c" style="color:#6a737d">//to IIS for higher throughput.</span>
<span class="pl-en" style="color:#6f42c1">ImageUltimateWebConfiguration.Current.CacheLocation</span> = &quot;~/App_Data/ImageCache&quot;;</pre>
</div>
<p style="margin-top:16px; margin-bottom:16px">Alternatively you can specify the configuration in&nbsp;<code style="font-family:SFMono-Regular,Consolas,&quot;Liberation Mono&quot;,Menlo,Courier,monospace; font-size:13.6px; padding:0.2em 0.4em; margin:0px">&lt;appSettings&gt;</code>&nbsp;tag
 of your Web.config.</p>
<div class="highlight highlight-text-xml" style="margin-bottom:16px">
<pre style="font-family:SFMono-Regular,Consolas,&quot;Liberation Mono&quot;,Menlo,Courier,monospace; font-size:13.6px; margin-top:0px; margin-bottom:0px; word-wrap:normal; padding:16px; overflow:auto; line-height:1.45; background-color:#f6f8fa; word-break:normal">&lt;<span class="pl-ent" style="color:#22863a">add</span> <span class="pl-e" style="color:#6f42c1">key</span>=<span class="pl-s" style="color:#032f62"><span class="pl-pds">&quot;</span>ImageUltimate:LicenseKey<span class="pl-pds">&quot;</span></span> <span class="pl-e" style="color:#6f42c1">value</span>=<span class="pl-s" style="color:#032f62"><span class="pl-pds">&quot;</span>QQJDJLJP34...<span class="pl-pds">&quot;</span></span> /&gt;
&lt;<span class="pl-ent" style="color:#22863a">add</span> <span class="pl-e" style="color:#6f42c1">key</span>=<span class="pl-s" style="color:#032f62"><span class="pl-pds">&quot;</span>ImageUltimateWeb:SourcePath<span class="pl-pds">&quot;</span></span> <span class="pl-e" style="color:#6f42c1">value</span>=<span class="pl-s" style="color:#032f62"><span class="pl-pds">&quot;</span>~/Content<span class="pl-pds">&quot;</span></span> /&gt;
&lt;<span class="pl-ent" style="color:#22863a">add</span> <span class="pl-e" style="color:#6f42c1">key</span>=<span class="pl-s" style="color:#032f62"><span class="pl-pds">&quot;</span>ImageUltimateWeb:CacheLocation<span class="pl-pds">&quot;</span></span> <span class="pl-e" style="color:#6f42c1">value</span>=<span class="pl-s" style="color:#032f62"><span class="pl-pds">&quot;</span>~/App_Data/ImageCache<span class="pl-pds">&quot;</span></span> /&gt;</pre>
</div>
<p style="margin-top:16px; margin-bottom:16px">As you would notice,&nbsp;<code style="font-family:SFMono-Regular,Consolas,&quot;Liberation Mono&quot;,Menlo,Courier,monospace; font-size:13.6px; padding:0.2em 0.4em; margin:0px">ImageUltimate:</code>&nbsp;prefix maps to&nbsp;<code style="font-family:SFMono-Regular,Consolas,&quot;Liberation Mono&quot;,Menlo,Courier,monospace; font-size:13.6px; padding:0.2em 0.4em; margin:0px">ImageUltimateConfiguration.Current</code>&nbsp;and&nbsp;<code style="font-family:SFMono-Regular,Consolas,&quot;Liberation Mono&quot;,Menlo,Courier,monospace; font-size:13.6px; padding:0.2em 0.4em; margin:0px">ImageUltimateWeb:</code>prefix
 maps to&nbsp;<code style="font-family:SFMono-Regular,Consolas,&quot;Liberation Mono&quot;,Menlo,Courier,monospace; font-size:13.6px; padding:0.2em 0.4em; margin:0px">ImageUltimateWebConfiguration.Current</code>.</p>
</li><li style="margin-top:0.25em">
<p style="margin-top:16px; margin-bottom:16px">Open one of your View pages (eg. Index.cshtml) and at the top of your page add the necessary namespaces:</p>
<div class="highlight highlight-source-cs" style="margin-bottom:16px">
<pre style="font-family:SFMono-Regular,Consolas,&quot;Liberation Mono&quot;,Menlo,Courier,monospace; font-size:13.6px; margin-top:0px; margin-bottom:0px; word-wrap:normal; padding:16px; overflow:auto; line-height:1.45; background-color:#f6f8fa; word-break:normal">@<span class="pl-k" style="color:#d73a49">using</span> <span class="pl-en" style="color:#6f42c1">GleamTech.ImageUltimate</span>
@<span class="pl-k" style="color:#d73a49">using</span> <span class="pl-en" style="color:#6f42c1">GleamTech.ImageUltimate.AspNet</span>
@<span class="pl-k" style="color:#d73a49">using</span> <span class="pl-en" style="color:#6f42c1">GleamTech.ImageUltimate.AspNet.Mvc</span></pre>
</div>
<p style="margin-top:16px; margin-bottom:16px">Alternatively you can add the namespaces globally in&nbsp;<span style="font-weight:600">Views/web.config</span>&nbsp;under<code style="font-family:SFMono-Regular,Consolas,&quot;Liberation Mono&quot;,Menlo,Courier,monospace; font-size:13.6px; padding:0.2em 0.4em; margin:0px">&lt;system.web.webPages.razor&gt;/&lt;pages&gt;/&lt;namespaces&gt;</code>&nbsp;tag
 to avoid adding namespaces in your pages every time:</p>
<div class="highlight highlight-text-xml" style="margin-bottom:16px">
<pre style="font-family:SFMono-Regular,Consolas,&quot;Liberation Mono&quot;,Menlo,Courier,monospace; font-size:13.6px; margin-top:0px; margin-bottom:0px; word-wrap:normal; padding:16px; overflow:auto; line-height:1.45; background-color:#f6f8fa; word-break:normal">&lt;<span class="pl-ent" style="color:#22863a">add</span> <span class="pl-e" style="color:#6f42c1">namespace</span>=<span class="pl-s" style="color:#032f62"><span class="pl-pds">&quot;</span>GleamTech.ImageUltimate<span class="pl-pds">&quot;</span></span> /&gt;
&lt;<span class="pl-ent" style="color:#22863a">add</span> <span class="pl-e" style="color:#6f42c1">namespace</span>=<span class="pl-s" style="color:#032f62"><span class="pl-pds">&quot;</span>GleamTech.ImageUltimate.AspNet<span class="pl-pds">&quot;</span></span> /&gt;
&lt;<span class="pl-ent" style="color:#22863a">add</span> <span class="pl-e" style="color:#6f42c1">namespace</span>=<span class="pl-s" style="color:#032f62"><span class="pl-pds">&quot;</span>GleamTech.ImageUltimate.AspNet.Mvc<span class="pl-pds">&quot;</span></span> /&gt;</pre>
</div>
<p style="margin-top:16px; margin-bottom:16px">Now in your page insert these lines:</p>
<div class="highlight highlight-source-cs" style="margin-bottom:16px">
<pre style="font-family:SFMono-Regular,Consolas,&quot;Liberation Mono&quot;,Menlo,Courier,monospace; font-size:13.6px; margin-top:0px; margin-bottom:0px; word-wrap:normal; padding:16px; overflow:auto; line-height:1.45; background-color:#f6f8fa; word-break:normal">@<span class="pl-c1" style="color:#005cc5">this</span>.<span class="pl-en" style="color:#6f42c1">ImageTag</span>(&quot;SomeImage.jpg&quot;, task =&gt; task.ResizeWidth(<span class="pl-c1" style="color:#005cc5">300</span>))</pre>
</div>
<p style="margin-top:16px; margin-bottom:16px">This will resize width of the source image &quot;~/Content/SomeImage.jpg&quot; to 300 pixels (keeping aspect ratio), cache the resulting image and render a&nbsp;<a href="https://github.com/GleamTech/ImageUltimate" target="_blank" style="background-color:transparent; color:#0366d6"><img src="null" alt="" style="max-width:100%"></a>&nbsp;tag
 in your page. For consecutive page views, the image will be served directly from the cache and no processing will be done. This is the reason the task (second parameter) is specified as a lambda function, it will be only called when necessary for maximum performance.
 Note that as we specified a non-rooted path for the image path (first parameter), the image is considered relative to ImageUltimateWebConfiguration.Current.SourcePath (as set in step 2). This allows you to write image commands as short lines and avoids parent
 path repetition.</p>
<p style="margin-top:16px; margin-bottom:16px">Sometimes you may need to render a url instead of a&nbsp;<a href="https://github.com/GleamTech/ImageUltimate" target="_blank" style="background-color:transparent; color:#0366d6"><img src="null" alt="" style="max-width:100%"></a>&nbsp;tag,
 then use:</p>
<div class="highlight highlight-source-cs" style="margin-bottom:16px">
<pre style="font-family:SFMono-Regular,Consolas,&quot;Liberation Mono&quot;,Menlo,Courier,monospace; font-size:13.6px; margin-top:0px; margin-bottom:0px; word-wrap:normal; padding:16px; overflow:auto; line-height:1.45; background-color:#f6f8fa; word-break:normal">@<span class="pl-c1" style="color:#005cc5">this</span>.<span class="pl-en" style="color:#6f42c1">ImageUrl</span>(&quot;SomeImage.jpg&quot;, task =&gt; task.ResizeWidth(<span class="pl-c1" style="color:#005cc5">300</span>))</pre>
</div>
<p style="margin-top:16px; margin-bottom:16px">For example, consider you want to add a background image to a CSS class:</p>
<div class="highlight highlight-text-html-basic" style="margin-bottom:16px">
<pre style="font-family:SFMono-Regular,Consolas,&quot;Liberation Mono&quot;,Menlo,Courier,monospace; font-size:13.6px; margin-top:0px; margin-bottom:0px; word-wrap:normal; padding:16px; overflow:auto; line-height:1.45; background-color:#f6f8fa; word-break:normal">&lt;<span class="pl-ent" style="color:#22863a">style</span>&gt;
<span class="pl-s1"><span class="pl-e" style="color:#6f42c1">.someCls</span></span>
<span class="pl-s1">{</span>
<span class="pl-s1">    <span class="pl-c1" style="color:#005cc5"><span class="pl-c1">background-image</span></span>: <span class="pl-c1" style="color:#005cc5">url</span>(<span class="pl-v" style="color:#e36209">@this.ImageUrl(</span><span class="pl-s" style="color:#032f62"><span class="pl-pds">&quot;</span>SomeImage.jpg<span class="pl-pds">&quot;</span></span><span class="pl-v" style="color:#e36209">,</span> <span class="pl-v" style="color:#e36209">task</span> <span class="pl-v" style="color:#e36209">=&gt;</span> <span class="pl-v" style="color:#e36209">task.ResizeWidth(300</span>)));</span>
<span class="pl-s1">}</span>
<span class="pl-s1">&lt;</span>/<span class="pl-ent" style="color:#22863a">style</span>&gt; </pre>
</div>
</li></ol>
<h3 style="margin-top:24px; margin-bottom:16px; font-size:1.25em; font-weight:600; line-height:1.25; color:#24292e">
<a id="user-content-to-use-imageultimate-in-an-aspnet-webforms-project-do-the-following-in-visual-studio" class="anchor" href="https://github.com/GleamTech/ImageUltimate#to-use-imageultimate-in-an-aspnet-webforms-project-do-the-following-in-visual-studio" style="background-color:transparent; color:#0366d6; float:left; padding-right:4px; margin-left:-20px; line-height:1"></a>To
 use ImageUltimate in an ASP.NET WebForms Project, do the following in Visual Studio:</h3>
<ol style="padding-left:2em; margin-top:0px; color:#24292e; font-size:16px; margin-bottom:0px!important">
<li>
<p style="margin-top:16px; margin-bottom:16px">Add references to ImageUltimate assemblies. There are two ways to perform this:</p>
<ul style="padding-left:2em; margin-top:0px; margin-bottom:0px">
<li>
<p style="margin-top:16px; margin-bottom:16px">Add reference to&nbsp;<span style="font-weight:600">GleamTech.Core.dll</span>&nbsp;and&nbsp;<span style="font-weight:600">GleamTech.ImageUltimate.dll</span>&nbsp;found in &quot;Bin&quot; folder of ImageUltimate-vX.X.X.X.zip
 package which you already downloaded and extracted.</p>
</li><li style="margin-top:0.25em">
<p style="margin-top:16px; margin-bottom:16px">Or install NuGet package and add references automatically via NuGet Package Manager in Visual Studio: Go to&nbsp;<span style="font-weight:600">Tools -&gt; NuGet Package Manager -&gt; Package Manager Console</span>&nbsp;and
 run this command:</p>
<p style="margin-top:16px; margin-bottom:16px"><code style="font-family:SFMono-Regular,Consolas,&quot;Liberation Mono&quot;,Menlo,Courier,monospace; font-size:13.6px; padding:0.2em 0.4em; margin:0px">Install-Package ImageUltimate -Source https://get.gleamtech.com/nuget/default/</code></p>
<p style="margin-top:16px; margin-bottom:16px">If you prefer using the user interface when working with NuGet, you can also install the package this way:</p>
<ul style="padding-left:2em; margin-top:0px; margin-bottom:0px">
<li>
<p style="margin-top:16px; margin-bottom:16px">&nbsp;GleamTech has its own NuGet feed so first you need to add this feed to be able to find GleamTech's packages. Go to&nbsp;<span style="font-weight:600">Tools -&gt; NuGet Package Manager -&gt; Package Manager
 Settings</span>&nbsp;and then click the&nbsp;<span style="font-weight:600">&#43;</span>&nbsp;button to add a new package source. Enter&nbsp;<code style="font-family:SFMono-Regular,Consolas,&quot;Liberation Mono&quot;,Menlo,Courier,monospace; font-size:13.6px; padding:0.2em 0.4em; margin:0px">GleamTech</code>&nbsp;in&nbsp;<span style="font-weight:600">Name</span>&nbsp;field
 and&nbsp;<code style="font-family:SFMono-Regular,Consolas,&quot;Liberation Mono&quot;,Menlo,Courier,monospace; font-size:13.6px; padding:0.2em 0.4em; margin:0px">https://get.gleamtech.com/nuget/default/</code>&nbsp;in&nbsp;<span style="font-weight:600">Source</span>field
 and click&nbsp;<span style="font-weight:600">OK</span>.</p>
</li><li style="margin-top:0.25em">
<p style="margin-top:16px; margin-bottom:16px">Go to&nbsp;<span style="font-weight:600">Tools -&gt; NuGet Package Manager -&gt; Manage NuGet Packages for Solution</span>, select&nbsp;<code style="font-family:SFMono-Regular,Consolas,&quot;Liberation Mono&quot;,Menlo,Courier,monospace; font-size:13.6px; padding:0.2em 0.4em; margin:0px">GleamTech</code>&nbsp;or&nbsp;<code style="font-family:SFMono-Regular,Consolas,&quot;Liberation Mono&quot;,Menlo,Courier,monospace; font-size:13.6px; padding:0.2em 0.4em; margin:0px">All</code>&nbsp;in
 the Package source dropdown on the top right. Now enter&nbsp;<code style="font-family:SFMono-Regular,Consolas,&quot;Liberation Mono&quot;,Menlo,Courier,monospace; font-size:13.6px; padding:0.2em 0.4em; margin:0px">ImageUltimate</code>&nbsp;in the search field, and click&nbsp;<span style="font-weight:600">Install</span>button
 on the found package.</p>
</li></ul>
</li></ul>
</li><li style="margin-top:0.25em">
<p style="margin-top:16px; margin-bottom:16px">Set ImageUltimate's global configuration. For example, you may want to set the license key and the default path for finding source images (SourcePath). Insert some of the following lines (if overriding a default
 value is required) into the&nbsp;<code style="font-family:SFMono-Regular,Consolas,&quot;Liberation Mono&quot;,Menlo,Courier,monospace; font-size:13.6px; padding:0.2em 0.4em; margin:0px">Application_Start</code>&nbsp;method of your&nbsp;<span style="font-weight:600">Global.asax.cs</span>:</p>
<div class="highlight highlight-source-cs" style="margin-bottom:16px">
<pre style="font-family:SFMono-Regular,Consolas,&quot;Liberation Mono&quot;,Menlo,Courier,monospace; font-size:13.6px; margin-top:0px; margin-bottom:0px; word-wrap:normal; padding:16px; overflow:auto; line-height:1.45; background-color:#f6f8fa; word-break:normal"><span class="pl-c" style="color:#6a737d">//Set this property only if you have a valid license key, otherwise do not</span>
<span class="pl-c" style="color:#6a737d">//set it so ImageUltimate runs in trial mode.</span>
<span class="pl-en" style="color:#6f42c1">ImageUltimateConfiguration.Current.LicenseKey</span> = &quot;QQJDJLJP34...&quot;;

<span class="pl-c" style="color:#6a737d">//The default SourcePath value is &quot;~/App_Data/ImageSource&quot;</span>
<span class="pl-c" style="color:#6a737d">//Both virtual and physical paths are allowed.</span>
<span class="pl-c" style="color:#6a737d">//Note that using a path under &quot;~/App_Data&quot; can have a benefit,</span>
<span class="pl-c" style="color:#6a737d">//for instance if you want to protect your original source files, i.e.</span>
<span class="pl-c" style="color:#6a737d">//prevent them from being downloaded directly, you can use this special </span>
<span class="pl-c" style="color:#6a737d">//folder which is restricted by ASP.NET runtime by default.</span>
<span class="pl-en" style="color:#6f42c1">ImageUltimateWebConfiguration.Current.SourcePath</span> = &quot;~/Content&quot;;

<span class="pl-c" style="color:#6a737d">//The default CacheLocation value is &quot;~/App_Data/ImageCache&quot;</span>
<span class="pl-c" style="color:#6a737d">//Both virtual and physical paths are allowed (or a Location instance for one of the supported </span>
<span class="pl-c" style="color:#6a737d">//file systems like Amazon S3 and Azure Blob).</span>
<span class="pl-c" style="color:#6a737d">//However it's recommended that you use a path inside your application folder </span>
<span class="pl-c" style="color:#6a737d">//(e.g. &quot;~/SomeFolder&quot;, &quot;/SomeFolder&quot; or &quot;C:\inetpub\wwwroot\MySite\SomeFolder&quot;)</span>
<span class="pl-c" style="color:#6a737d">//so that ImageUltimate can use RewritePath to pass download requests directly</span>
<span class="pl-c" style="color:#6a737d">//to IIS for higher throughput.</span>
<span class="pl-en" style="color:#6f42c1">ImageUltimateWebConfiguration.Current.CacheLocation</span> = &quot;~/App_Data/ImageCache&quot;; </pre>
</div>
<p style="margin-top:16px; margin-bottom:16px">Alternatively you can specify the configuration in&nbsp;<code style="font-family:SFMono-Regular,Consolas,&quot;Liberation Mono&quot;,Menlo,Courier,monospace; font-size:13.6px; padding:0.2em 0.4em; margin:0px">&lt;appSettings&gt;</code>&nbsp;tag
 of your Web.config.</p>
<div class="highlight highlight-text-xml" style="margin-bottom:16px">
<pre style="font-family:SFMono-Regular,Consolas,&quot;Liberation Mono&quot;,Menlo,Courier,monospace; font-size:13.6px; margin-top:0px; margin-bottom:0px; word-wrap:normal; padding:16px; overflow:auto; line-height:1.45; background-color:#f6f8fa; word-break:normal">&lt;<span class="pl-ent" style="color:#22863a">add</span> <span class="pl-e" style="color:#6f42c1">key</span>=<span class="pl-s" style="color:#032f62"><span class="pl-pds">&quot;</span>ImageUltimate:LicenseKey<span class="pl-pds">&quot;</span></span> <span class="pl-e" style="color:#6f42c1">value</span>=<span class="pl-s" style="color:#032f62"><span class="pl-pds">&quot;</span>QQJDJLJP34...<span class="pl-pds">&quot;</span></span> /&gt;
&lt;<span class="pl-ent" style="color:#22863a">add</span> <span class="pl-e" style="color:#6f42c1">key</span>=<span class="pl-s" style="color:#032f62"><span class="pl-pds">&quot;</span>ImageUltimateWeb:SourcePath<span class="pl-pds">&quot;</span></span> <span class="pl-e" style="color:#6f42c1">value</span>=<span class="pl-s" style="color:#032f62"><span class="pl-pds">&quot;</span>~/Content<span class="pl-pds">&quot;</span></span> /&gt;
&lt;<span class="pl-ent" style="color:#22863a">add</span> <span class="pl-e" style="color:#6f42c1">key</span>=<span class="pl-s" style="color:#032f62"><span class="pl-pds">&quot;</span>ImageUltimateWeb:CacheLocation<span class="pl-pds">&quot;</span></span> <span class="pl-e" style="color:#6f42c1">value</span>=<span class="pl-s" style="color:#032f62"><span class="pl-pds">&quot;</span>~/App_Data/ImageCache<span class="pl-pds">&quot;</span></span> /&gt;</pre>
</div>
<p style="margin-top:16px; margin-bottom:16px">As you would notice,&nbsp;<code style="font-family:SFMono-Regular,Consolas,&quot;Liberation Mono&quot;,Menlo,Courier,monospace; font-size:13.6px; padding:0.2em 0.4em; margin:0px">ImageUltimate:</code>&nbsp;prefix maps to&nbsp;<code style="font-family:SFMono-Regular,Consolas,&quot;Liberation Mono&quot;,Menlo,Courier,monospace; font-size:13.6px; padding:0.2em 0.4em; margin:0px">ImageUltimateConfiguration.Current</code>&nbsp;and&nbsp;<code style="font-family:SFMono-Regular,Consolas,&quot;Liberation Mono&quot;,Menlo,Courier,monospace; font-size:13.6px; padding:0.2em 0.4em; margin:0px">ImageUltimateWeb:</code>prefix
 maps to&nbsp;<code style="font-family:SFMono-Regular,Consolas,&quot;Liberation Mono&quot;,Menlo,Courier,monospace; font-size:13.6px; padding:0.2em 0.4em; margin:0px">ImageUltimateWebConfiguration.Current</code>.</p>
</li><li style="margin-top:0.25em">
<p style="margin-top:16px; margin-bottom:16px">Open one of your pages (eg. Default.aspx) and at the top of your page add add the necessary namespaces:</p>
<div class="highlight highlight-text-html-asp" style="margin-bottom:16px">
<pre style="font-family:SFMono-Regular,Consolas,&quot;Liberation Mono&quot;,Menlo,Courier,monospace; font-size:13.6px; margin-top:0px; margin-bottom:0px; word-wrap:normal; padding:16px; overflow:auto; line-height:1.45; background-color:#f6f8fa; word-break:normal"><span class="pl-s1"><span class="pl-pse">&lt;%</span>@ Import Namespace<span class="pl-k" style="color:#d73a49">=</span><span class="pl-s" style="color:#032f62"><span class="pl-pds">&quot;</span>GleamTech.ImageUltimate<span class="pl-pds">&quot;</span></span> <span class="pl-pse">%&gt;</span></span>
<span class="pl-s1"><span class="pl-pse">&lt;%</span>@ Import Namespace<span class="pl-k" style="color:#d73a49">=</span><span class="pl-s" style="color:#032f62"><span class="pl-pds">&quot;</span>GleamTech.ImageUltimate.AspNet<span class="pl-pds">&quot;</span></span> <span class="pl-pse">%&gt;</span></span>
<span class="pl-s1"><span class="pl-pse">&lt;%</span>@ Import Namespace<span class="pl-k" style="color:#d73a49">=</span><span class="pl-s" style="color:#032f62"><span class="pl-pds">&quot;</span>GleamTech.ImageUltimate.AspNet.WebForms<span class="pl-pds">&quot;</span></span> <span class="pl-pse">%&gt;</span></span></pre>
</div>
<p style="margin-top:16px; margin-bottom:16px">Alternatively you can add the namespaces globally in&nbsp;<span style="font-weight:600">Web.config</span>&nbsp;under&nbsp;<code style="font-family:SFMono-Regular,Consolas,&quot;Liberation Mono&quot;,Menlo,Courier,monospace; font-size:13.6px; padding:0.2em 0.4em; margin:0px">&lt;system.web&gt;/&lt;pages&gt;/&lt;namespaces&gt;</code>&nbsp;tag
 to avoid adding namespaces in your pages every time:</p>
<div class="highlight highlight-text-xml" style="margin-bottom:16px">
<pre style="font-family:SFMono-Regular,Consolas,&quot;Liberation Mono&quot;,Menlo,Courier,monospace; font-size:13.6px; margin-top:0px; margin-bottom:0px; word-wrap:normal; padding:16px; overflow:auto; line-height:1.45; background-color:#f6f8fa; word-break:normal">&lt;<span class="pl-ent" style="color:#22863a">add</span> <span class="pl-e" style="color:#6f42c1">namespace</span>=<span class="pl-s" style="color:#032f62"><span class="pl-pds">&quot;</span>GleamTech.ImageUltimate<span class="pl-pds">&quot;</span></span> /&gt;
&lt;<span class="pl-ent" style="color:#22863a">add</span> <span class="pl-e" style="color:#6f42c1">namespace</span>=<span class="pl-s" style="color:#032f62"><span class="pl-pds">&quot;</span>GleamTech.ImageUltimate.AspNet<span class="pl-pds">&quot;</span></span> /&gt;
&lt;<span class="pl-ent" style="color:#22863a">add</span> <span class="pl-e" style="color:#6f42c1">namespace</span>=<span class="pl-s" style="color:#032f62"><span class="pl-pds">&quot;</span>GleamTech.ImageUltimate.AspNet.WebForms<span class="pl-pds">&quot;</span></span> /&gt;</pre>
</div>
<p style="margin-top:16px; margin-bottom:16px">Now in your page insert these lines:</p>
<div class="highlight highlight-text-html-asp" style="margin-bottom:16px">
<pre style="font-family:SFMono-Regular,Consolas,&quot;Liberation Mono&quot;,Menlo,Courier,monospace; font-size:13.6px; margin-top:0px; margin-bottom:0px; word-wrap:normal; padding:16px; overflow:auto; line-height:1.45; background-color:#f6f8fa; word-break:normal"><span class="pl-s1"><span class="pl-pse">&lt;%=</span>this.ImageTag(<span class="pl-s" style="color:#032f62"><span class="pl-pds">&quot;</span>SomeImage.jpg<span class="pl-pds">&quot;</span></span>, task <span class="pl-k" style="color:#d73a49">=&gt;</span> task.ResizeWidth(<span class="pl-c1" style="color:#005cc5">300</span>))<span class="pl-pse">%&gt;</span></span></pre>
</div>
<p style="margin-top:16px; margin-bottom:16px">This will resize width of the source image &quot;~/Content/SomeImage.jpg&quot; to 300 pixels (keeping aspect ratio), cache the resulting image and render a&nbsp;<a href="https://github.com/GleamTech/ImageUltimate" target="_blank" style="background-color:transparent; color:#0366d6"><img src="null" alt="" style="max-width:100%"></a>&nbsp;tag
 in your page. For consecutive page views, the image will be served directly from the cache and no processing will be done. This is the reason the task (second parameter) is specified as a lambda function, it will be only called when necessary for maximum performance.
 Note that as we specified a non-rooted path for the image path (first parameter), the image is considered relative to ImageUltimateWebConfiguration.Current.SourcePath (as set in step 2). This allows you to write image commands as short lines and avoids parent
 path repetition.</p>
<p style="margin-top:16px; margin-bottom:16px">Sometimes you may need to render a url instead of a&nbsp;<a href="https://github.com/GleamTech/ImageUltimate" target="_blank" style="background-color:transparent; color:#0366d6"><img src="null" alt="" style="max-width:100%"></a>&nbsp;tag,
 then use:</p>
<div class="highlight highlight-text-html-asp" style="margin-bottom:16px">
<pre style="font-family:SFMono-Regular,Consolas,&quot;Liberation Mono&quot;,Menlo,Courier,monospace; font-size:13.6px; margin-top:0px; margin-bottom:0px; word-wrap:normal; padding:16px; overflow:auto; line-height:1.45; background-color:#f6f8fa; word-break:normal"><span class="pl-s1"><span class="pl-pse">&lt;%=</span>this.ImageUrl(<span class="pl-s" style="color:#032f62"><span class="pl-pds">&quot;</span>SomeImage.jpg<span class="pl-pds">&quot;</span></span>, task <span class="pl-k" style="color:#d73a49">=&gt;</span> task.ResizeWidth(<span class="pl-c1" style="color:#005cc5">300</span>))<span class="pl-pse">%&gt;</span></span></pre>
</div>
<p style="margin-top:16px; margin-bottom:16px">For example, consider you want to add a background image to a CSS class:</p>
<div class="highlight highlight-text-html-basic" style="margin-bottom:16px">
<pre style="font-family:SFMono-Regular,Consolas,&quot;Liberation Mono&quot;,Menlo,Courier,monospace; font-size:13.6px; margin-top:0px; margin-bottom:0px; word-wrap:normal; padding:16px; overflow:auto; line-height:1.45; background-color:#f6f8fa; word-break:normal">&lt;<span class="pl-ent" style="color:#22863a">style</span>&gt;
<span class="pl-s1">    <span class="pl-e" style="color:#6f42c1">.someCls</span></span>
<span class="pl-s1">    {</span>
<span class="pl-s1">        <span class="pl-c1" style="color:#005cc5"><span class="pl-c1">background-image</span></span>: <span class="pl-c1" style="color:#005cc5">url</span>(<span class="pl-v" style="color:#e36209">&lt;%=this.ImageUrl(</span><span class="pl-s" style="color:#032f62"><span class="pl-pds">&quot;</span>SomeImage.jpg<span class="pl-pds">&quot;</span></span><span class="pl-v" style="color:#e36209">,</span> <span class="pl-v" style="color:#e36209">task</span> <span class="pl-v" style="color:#e36209">=&gt;</span> <span class="pl-v" style="color:#e36209">task.ResizeWidth(300</span>))%&gt;);</span>
<span class="pl-s1">    }</span>
<span class="pl-s1">&lt;</span>/<span class="pl-ent" style="color:#22863a">style</span>&gt;</pre>
</div>
</li></ol>
</div>

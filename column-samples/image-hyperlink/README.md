# Changing image hyperlink standard behavior

## Summary
If you click on an image in a Sharepoint list, the image is displayed as a preview. This formatter changes the standard behavior in which a link from another column is used. In this way, a click on the image has the same behavior as if the link had been clicked directly.

![screenshot of the sample](./assets/screenshot.png)

## View requirements
- A column of type image containing this column formatter
- A hyperlink column containing the new target link

Solution|Author(s)
--------|---------
image-hyperlink.json | [Hagen Deike](https://github.com/samurai-ka) ([@samurai@sueden.social](https://sueden.social/@samurai))

## Version history

Version|Date|Comments
-------|----|--------
1.0|November 15, 2024|Initial release

## Disclaimer

**THIS CODE IS PROVIDED *AS IS* WITHOUT WARRANTY OF ANY KIND, EITHER EXPRESS OR IMPLIED, INCLUDING ANY IMPLIED WARRANTIES OF FITNESS FOR A PARTICULAR PURPOSE, MERCHANTABILITY, OR NON-INFRINGEMENT.**

---

## Additional notes
Any potential additional notes to get included in the readme around the sample with additional pictures etc.
- Change the Image size on line 21
- Don't need rounded corners? Remove the image style on line 24-26
- Padding between the rows can be tweaked on line 6 & 7

<img src="https://pnptelemetry.azurewebsites.net/list-formatting/column-samples/image-hyperlink" />
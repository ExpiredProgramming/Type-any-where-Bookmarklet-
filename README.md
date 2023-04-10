# Type-any-where-Bookmarklet-
javascript:
if (document.designMode === "on") {
  document.designMode = "off";
} else {
  document.body.contentEditable = 'true';
  document.designMode = 'on';
}
void 0;

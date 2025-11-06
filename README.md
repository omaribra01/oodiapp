<!DOCTYPE html>
<html>
<head>
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <script>
    var userAgent = navigator.userAgent || navigator.vendor || window.opera;

    if (/android/i.test(userAgent)) {
      // Redirect Android users to Google Play
      window.location.href = "https://play.google.com/store/apps/details?id=iq.oodi.com&pli=1";
    } else if (/iPad|iPhone|iPod/.test(userAgent) && !window.MSStream) {
      // Redirect iOS users to App Store
      window.location.href = "https://apps.apple.com/iq/app/oodi-%D8%A3%D9%88%D9%88%D8%AF%D9%8A/id1557687474";
    } else {
      // Default redirect (web or unknown OS)
      window.location.href = "https://play.google.com/store/apps/details?id=iq.oodi.com&pli=1";
    }
  </script>
</head>
<body>
</body>
</html>

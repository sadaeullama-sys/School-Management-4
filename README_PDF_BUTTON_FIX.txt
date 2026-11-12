PDF BUTTON FIX - IMPORTANT
1. Fixed a recursive PDF theme color getter. The Classic Blue option previously referred to itself,
   which could cause PDF generation to fail immediately when the user tapped a PDF action.
2. Added visible "Preparing PDF..." feedback, a progress indicator, duplicate-tap protection,
   and an on-screen error message if PDF generation/share fails.
3. Kept the four existing PDF actions and Printing.sharePdf output flow.
4. APK has NOT been built or tested on a physical device. Build a new release AAB/APK using GitHub Actions,
   install/test the APK, and only then upload the new signed AAB to Play Console.

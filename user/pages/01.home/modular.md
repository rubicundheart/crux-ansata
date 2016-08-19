---
title: Home

onpage_menu: false
content:
    items: @self.modular
    order:
        by: default
        dir: asc
        custom:
            - _events
            - _about
---
<a href="#" id="open-mc-popup" onclick ="showMailingPopUp(); return false;">Sign up for newsletter!</a>
<!-- MAILCHIMP MODAL FORM -->
 <script type="text/javascript" src="//s3.amazonaws.com/downloads.mailchimp.com/js/signup-forms/popup/embed.js" data-dojo-config="usePlainJson: true, isDebug: false"></script>
 <script>function showMailingPopUp() {
 require(["mojo/signup-forms/Loader"], function(L) { L.start({"baseUrl":"mc.us13.list-manage.com","uuid":"2cf9a968d70230ef789606d7f",
 "lid":"d665f91ec7"}) })
 document.cookie = "MCEvilPopupClosed=; expires=Thu, 01 Jan 1970 00:00:00 UTC";
 };</script>

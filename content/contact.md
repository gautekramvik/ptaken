+++
title = "Kontakt"
id = "contact"
+++

# Vi er her for å hjelpe Dem!

Lurer du på noe? Vi er her for å hjelpe Dem med nærsagt hva som helst! Hva. Som. Helst. Trenger du en hardisk med SharePoint? Vi har det. Trenger du en hardisk med CRM? Vi har det også. Begynner du å gå tom for Powershell i hardisken din? Ta det helt med ro, våre vakre konsulenter fyller opp tanken så full av Powershell at den flommer over!


<!-- PowerWebForm <head> -->
<script src="https://pocloudcentral.crm.powerobjects.net/PowerWebForm/scripts/jquery-1.9.0.validate.min.js" type="text/javascript"></script>
<script src="https://pocloudcentral.crm.powerobjects.net/PowerWebForm/scripts/jquery-ui-1.8.17.custom.min.js" type="text/javascript"></script>

<!-- PowerWebForm </head> -->

</head>
<!-- PowerWebForm <body> -->

<form id="powf_C1A7E4AD58D0E711A94B000D3A246B2E" class="left"
enctype="multipart/form-data" action="https://pocloudcentral.crm.powerobjects.net/PowerWebForm/PowerWebFormData.aspx?t=nOfWFL70TUquX9DRvqN83m4AbwB2AGEAbgBlAHQAYQBzADIA&formId=powf_C1A7E4AD58D0E711A94B000D3A246B2E&tver=2013&c=1"
method="post">

<div class="label">
<label for="powf_c200de5e5fd0e711a94b000d3a246b2e">CUSTOM CRM SKJEMA-TEST <font class="required">*</font></label>
<span class="tip"></span>
<div class="clear"></div>
</div>

<div class="field">
<input type="text" id="powf_c200de5e5fd0e711a94b000d3a246b2e" name="powf_c200de5e5fd0e711a94b000d3a246b2e" value="" maxlength="100" class="required" />
<div class="clear"></div>
</div>

<div class="clear"></div>

<!-- skjult -->
<input type="hidden" id="powf_1719ad9e5fd0e711a94b000d3a246b2e" name="powf_1719ad9e5fd0e711a94b000d3a246b2e" value="test@test.no" />
<input type="hidden" name="ignore_submitmessage" value="Takk for meldingen din!" />
<input type="hidden" name="ignore_linkbuttontext" value="Ta meg tilbake, er De snill" />
<input type="hidden" name="ignore_redirecturl" value="https://gautekramvik.github.io/ptaken" />
<input type="hidden" name="ignore_redirectmode" value="Button" />
<div align="center">
    <input class="button" type="submit" value="Kontakt meg"
        onclick="javascript:;" />
</div>
</form>
<script type="text/javascript">
$(document).ready(function () {
jQuery.extend(jQuery.validator.messages, {
email:"Please enter a valid email address. Make sure there are no leading or trailing spaces."
});
$("#powf_C1A7E4AD58D0E711A94B000D3A246B2E").validate({
errorPlacement: function(error, element) {
error.appendTo( element.parents("div.field:first").find("div.clear:first") );
},
invalidHandler: function(event, validator) {
var errors = validator.numberOfInvalids();
if (errors) {
$("input[type=submit]").removeAttr("disabled");
}
},
onfocusout: false,
onkeyup: false,
onclick: false,
debug: false
});
});
</script>
<!-- PowerWebForm </body> -->

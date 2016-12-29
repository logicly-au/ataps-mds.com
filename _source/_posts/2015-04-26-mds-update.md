---
title: 'MDS Update'
changed: '2015-04-26T20:50:36.'
---

<p>MDS Update v4.175 has been released.</p>
<p>The following new features will be available</p>
<ul>
<li>A new conclusion "Patient ineligible" was added. This conclusion may only be selected if there are NO sessions associated with the referral. Further instructions on when this conclusion option is applicable can be found in the <a href="../../user-documentation/recording-of-ineligible-patients-at-triage-stage/index.html" target="_top">documentation</a>.</li>
</ul>
<ul>
<li>Allowing uploads of multiple sessions on the same day. An optional field "org_ses_id" has been added to the session upload format to resolve issues related to patients having multiple sessions delivered on the same day for a referral. If you require this feature please contact <a href="mailto:support@ataps-mds.com">support@ataps-mds.com</a> for more information.</li>
</ul>
<p>The following were identified as part of the ongoing improvements in ATAPS data quality</p>
<ul>
<li>Patient keys, Referrer nicknames and MHPro nicknames are consistently validated to be between 2 and 50 printable ASCII characters in length.</li>
</ul>
<ul>
<li>Session uploads will no longer accept an empty string as a valid response for the fields "type" or "modality". Either the "duration" or "no_show" must have a non-zero value.</li>
</ul>
<p>The documentation at <a href="../../technical-documentation/index.html" target="_top">https://ataps-mds.com/mds/technical-documentation/</a> has been updated to reflect these changes.</p>    

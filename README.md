test1
=====
<p><b><font size="5">Welcome to $GatewayName!</font></b></p>

<p><b><font size="2">Read the following terms and conditions, 
and hit the I Agree to proceed.</font></b></p>
 <p><font size="2">...</font></p>

<form name="login" method="post" action="http://192.168.1.1:5280/">
<input type="hidden" name="accept_terms" value="yes" />      
<input type="hidden" name="redirect" value="$redirect">
<input type="hidden" name="mode_login">
<input type="submit" value="I Agree">
</form>

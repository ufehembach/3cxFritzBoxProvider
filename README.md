# 3cxFritzBoxProvider
this is a try for an provider template for 3cx v20 to connect to a FritzBox with special settings

following: https://www.youtube.com/watch?v=IRWZ7Ev4yYU (thanks at this point), I modified the following


      <!--<field name="ParameterOut" custom="" parameter="ContactUser">$OutboundCallerId</field>-->
      <field name="ParameterOut" custom="" parameter="ContactUser">$AuthID</field>
      
      <!--<field name="ParameterOut" custom="" parameter="FromDisplayName">$OutboundCallerId</field>-->
      <field name="ParameterOut" custom="" parameter="FromDisplayName">$OriginatorCallerId</field>
      <!--<field name="ParameterOut" custom="" parameter="FromUserPart">$OutboundCallerId</field>-->
      <field name="ParameterOut" custom="" parameter="FromUserPart">$AuthID</field>


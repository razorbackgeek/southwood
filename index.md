<!DOCTYPE html PUBLIC "-//W3C//DTD HTML 4.01 Transitional//EN">
<html><head>
    <meta http-equiv="content-type" content="text/html; charset=windows-1252">
    <script type="text/javascript">window["_gaUserPrefs"] = { ioo : function() { return true; } }</script>
    <title>Data Aquisition Module</title>
    <style>.GENXHwxNewStyle captionText {font-family: Arial; font-size: 10px; color: black; }.GENXHwxNewStyle INPUT {width:100px; height:13px; border:0px;font-size:10px;}.GENXHwxNewStyle INPUT.GENXHgoButton {width:28px; height:19px; border:0px;}.GENXHwxNewStyle TD.GENXHcaptionText {font-family: Arial; font-size: 10px; color: black; }.GENXHwxNewStyle TD,A.GENXHvertLinks,A.GENXHvertLinks:link,A.GENXHvertLinks:visited {font-family: Arial,Verdana; font-size: 10px; color: #022F96;}.GENXHwxNewStyle A.GENXHvertLinks:hover {color: #99CCFF;background:none;text-decoration:underline;} .GENXHwxNewStyle A.GENXHsmLinks,A.GENXHsmLinks:link,A.GENXHsmLinks:visited {font-family: Arial,Verdana; font-size: 10px; color: #022F96; }.GENXHwxNewStyle A.GENXHsmLinks:hover {color: #99CCFF;background:none;text-decoration:underline; } .GENXHwxNewStyle FONT.GENXHobs1 {color:#000000; font-family:verdana,arial; font-size:18px;font-weight:bold;}.GENXHwxNewStyle FONT.GENXHobs2 {color:#000000; font-family:verdana; font-size:10px;}.GENXHwxNewStyle TD.obsWx {font-family: Arial;font-size: 11px; color:#000000;font-weight:bold;}.GENXHwxNewStyle A.GENXHcityInfo,A.GENXHcityInfo:link,A.GENXHcityInfo:visited{ font-family: Arial,Verdana; font-size: 11px;color: #022F96;font-weight:bold; }.GENXHwxNewStyle A.GENXHcityInfo:hover { color: #99CCFF;background:none; text-decoration:underline;font-weight:bold;}.GENXHwxNewStyle A.GENXHalertInfo,A.alertInfo:link,A.alertInfo:visited{ font-family: Arial,Verdana; font-size: 11px;color: red;}.GENXHwxNewStyle A.alertInfo:hover { color: #99CCFF;background:none;text-decoration:underline; }.GENXHwxNewStyle A.blkVerdanaText11 {font-family:verdana,arial,helvetica; font-size: 11px; color: #000000; } .GENXHnavOut{ cursor: pointer}</style>
    <style>.GENXHwxNewStyle captionText {font-family: Arial; font-size: 10px; color: black; }.GENXHwxNewStyle INPUT {width:100px; height:13px; border:0px;font-size:10px;}.GENXHwxNewStyle INPUT.GENXHgoButton {width:28px; height:19px; border:0px;}.GENXHwxNewStyle TD.GENXHcaptionText {font-family: Arial; font-size: 10px; color: black; }.GENXHwxNewStyle TD,A.GENXHvertLinks,A.GENXHvertLinks:link,A.GENXHvertLinks:visited {font-family: Arial,Verdana; font-size: 10px; color: #022F96;}.GENXHwxNewStyle A.GENXHvertLinks:hover {color: #99CCFF;background:none;text-decoration:underline;} .GENXHwxNewStyle A.GENXHsmLinks,A.GENXHsmLinks:link,A.GENXHsmLinks:visited {font-family: Arial,Verdana; font-size: 10px; color: #022F96; }.GENXHwxNewStyle A.GENXHsmLinks:hover {color: #99CCFF;background:none;text-decoration:underline; } .GENXHwxNewStyle FONT.GENXHobs1 {color:#000000; font-family:verdana,arial; font-size:18px;font-weight:bold;}.GENXHwxNewStyle FONT.GENXHobs2 {color:#000000; font-family:verdana; font-size:10px;}.GENXHwxNewStyle TD.obsWx {font-family: Arial;font-size: 11px; color:#000000;font-weight:bold;}.GENXHwxNewStyle A.GENXHcityInfo,A.GENXHcityInfo:link,A.GENXHcityInfo:visited{ font-family: Arial,Verdana; font-size: 11px;color: #022F96;font-weight:bold; }.GENXHwxNewStyle A.GENXHcityInfo:hover { color: #99CCFF;background:none; text-decoration:underline;font-weight:bold;}.GENXHwxNewStyle A.GENXHalertInfo,A.alertInfo:link,A.alertInfo:visited{ font-family: Arial,Verdana; font-size: 11px;color: red;}.GENXHwxNewStyle A.alertInfo:hover { color: #99CCFF;background:none;text-decoration:underline; }.GENXHwxNewStyle A.blkVerdanaText11 {font-family:verdana,arial,helvetica; font-size: 11px; color: #000000; } .GENXHnavOut{ cursor: pointer}</style>
    <style>.OTDRHwxNewStyle captionText {font-family: Arial; font-size: 10px; color: black; }.OTDRHwxNewStyle INPUT {width:100px; height:13px; border:0px;font-size:10px;}.OTDRHwxNewStyle INPUT.OTDRHgoButton {width:28px; height:19px; border:0px;}.OTDRHwxNewStyle TD.OTDRHcaptionText {font-family: Arial; font-size: 10px; color: black; }.OTDRHwxNewStyle TD,A.OTDRHvertLinks,A.OTDRHvertLinks:link,A.OTDRHvertLinks:visited {font-family: Arial,Verdana; font-size: 10px; color: #F6DA86;}.OTDRHwxNewStyle A.OTDRHvertLinks:hover {color: #99CCFF;background:none;text-decoration:underline;} .OTDRHwxNewStyle A.OTDRHsmLinks,A.OTDRHsmLinks:link,A.OTDRHsmLinks:visited {font-family: Arial,Verdana; font-size: 10px; color: #F6DA86; }.OTDRHwxNewStyle A.OTDRHsmLinks:hover {color: #99CCFF;background:none;text-decoration:underline; } .OTDRHwxNewStyle FONT.OTDRHobs1 {color:#000000; font-family:verdana,arial; font-size:18px;font-weight:bold;}.OTDRHwxNewStyle FONT.OTDRHobs2 {color:#000000; font-family:verdana; font-size:10px;}.OTDRHwxNewStyle TD.OTDRHobsWx {font-family: Arial;font-size: 11px; color:#000000;font-weight:bold;}.OTDRHwxNewStyle A.OTDRHcityInfo,A.OTDRHcityInfo:link,A.OTDRHcityInfo:visited{ font-family: Arial,Verdana; font-size: 11px;color: #FFFFFF;font-weight:bold; }.OTDRHwxNewStyle A.OTDRHcityInfo:hover { color: #99CCFF;background:none; text-decoration:underline;font-weight:bold;}.OTDRHwxNewStyle A.OTDRHalertInfo,A.OTDRHalertInfo:link,A.OTDRHalertInfo:visited{ font-family: Arial,Verdana; font-size: 11px;color: red;}.OTDRHwxNewStyle A.OTDRHalertInfo:hover { color: #99CCFF;background:none;text-decoration:underline; }.OTDRHwxNewStyle A.OTDRHblkVerdanaText11 {font-family:verdana,arial,helvetica; font-size: 11px; color: #000000; } .OTDRHnavOut{ cursor: pointer}</style>
  </head>
  <body style="color: rgb(221, 221, 221); background-color: rgb(32, 53, 80);" vlink="#dddddd" topmargin="0" link="#dddddd" leftmargin="0" background="index_files/background.htm" alink="#ffffff">
    <table width="100%" height="90%" border="0">
      <tbody>
        <tr>
          <td width="50%" height="80%" align="center"> <br>
            <!-- BEGIN SEARCH FORMS -->
            <table width="80%" height="95%" cellspacing="0" cellpadding="1" border="0">
              <tbody>
                <tr>
                  <td width="40%" valign="top" height="7%"> <font size="3" face="arial"><a href="http://www.google.com/" target="_top"><i><b>Google</b></i></a></font>
                  </td>
                  <td valign="top" align="right">
                    <form action="http://www.google.com/search" method="get" name="f" target="_top"> <input name="q" size="40" maxlength="256" type="text"> <input name="btnG" value="Google Search" type="hidden">
                    </form>
                  </td>
                </tr>
                <tr>
                  <td width="40%" valign="top" height="7%"> <font size="3" face="arial"><a href="http://images.google.com/" target="_top"><i><b>Google
                            Images</b></i></a></font> </td>
                  <td valign="top" align="right">
                    <form method="get" action="http://images.google.com/images" target="_top"> <input name="q" size="40" maxlength="255" type="text"> <input name="btnG" value="Google Search" type="hidden">
                    </form>
                  </td>
                </tr>
                <tr>
                  <td width="40%" valign="top" height="7%"> <font size="3" face="arial"><a href="http://us.imdb.com/" target="_top"><i><b>IMDB</b></i></a></font>
                  </td>
                  <td valign="top" align="right">
                    <form action="http://www.imdb.com/find" target="_top"> <input name="q" size="40" type="text"> </form>
                  </td>
                </tr>
                <tr>
                  <td width="40%" valign="top" height="7%"> <font size="3" face="arial"><a href="http://www.ebay.com/" target="_top"><i><b>eBay</b></i></a></font>
                  </td>
                  <td valign="top" align="right">
                    <form method="get" action="http://search.ebay.com//search/search.dll" target="_top"> <input name="query" maxlength="100" size="40" type="text"> <input name="product" value="all" type="hidden">
                    </form>
                  </td>
                </tr>
                <tr>
                  <td width="40%" valign="top" height="7%"> <font size="3" face="arial"><a href="http://www.newegg.com/" target="_top"><i><b>Newegg</b></i></a></font>
                  </td>
                  <td valign="top" align="right">
                    <form action="http://www.newegg.com/Product/ProductList.asp" method="get" name="UISearch" target="_top"> <input name="Submit" value="Go" type="hidden"> <input id="Search-1" name="description" size="40" type="text"> </form>
                  </td>
                </tr>
                <tr>
                  <td width="40%" valign="top" height="7%"> <font size="3" face="arial"><a href="http://www.torrentspy.com/directory.asp" target="_top"><i><b>TorrentSpy</b></i></a></font> </td>
                  <td valign="top" align="right">
                    <form method="get" action="http://www.torrentspy.com/search.asp" target="_top"> <input size="40" name="query" type="text">
                      <input name="submit" type="hidden"> </form>
                  </td>
                </tr>
                <tr>
                  <td width="40%" valign="top" height="7%"> <font size="3" face="arial"><a href="http://thepiratebay.org/browse.php" target="_top"><i><b>The
Pirate
                            Bay</b></i></a></font> </td>
                  <td valign="top" align="right">
                    <form method="get" name="q" action="http://thepiratebay.org/search.php" target="_top"> <input size="40" name="q" type="text"> <input name="submit" type="hidden"> </form>
                  </td>
                </tr>
                <tr>
                  <td width="40%" valign="top" height="7%"> <font size="3" face="arial"><a href="http://www.newzbin.com/" target="_top"><i><b>Newzbin</b></i></a></font>
                  </td>
                  <td valign="top" align="right">
                    <form class="searchForm" method="get" action="http://www.newzbin.com/search/query/p/" target="_top"> <input size="40" name="q" type="text"> <input value="-1" name="Category" type="hidden"> <input value="Search" tabindex="4" type="hidden"> </form>
                  </td>
                </tr>
                <tr>
                  <td width="40%" valign="top" height="7%"> <font size="3" face="arial"><a href="http://alt.binaries.nl/" target="_top"><i><b>alt.binaries.nl</b></i></a></font>
                  </td>
                  <td valign="top" align="right">
                    <form method="get" action="http://alt.binaries.nl/search/" name="sb" target="_top"> <input size="40" name="q" type="text"> <input value="Search" type="hidden"> </form>
                  </td>
                </tr>
                <tr>
                  <td width="40%" valign="top" height="7%"> <font size="3" face="arial"><a href="http://www.youtube.com/" target="_top"><i><b>Youtube</b></i></a></font>
                  </td>
                  <td valign="top" align="right">
                    <form id="search_form" action="http://www.youtube.com/results" method="get" target="_top"> <input name="search_query" value="submit" type="hidden"> <input id="search" name="search" size="40" type="text"> </form>
                  </td>
                </tr>
                <tr>
                  <td width="40%" valign="top" height="7%"> <font size="3" face="arial"><a href="http://en.wikipedia.org/wiki/Main_Page" target="_top"><i><b>Wikipedia</b></i></a></font> </td>
                  <td valign="top" align="right">
                    <form name="searchform" action="http://en.wikipedia.org/wiki/Special:Search" id="searchform" target="_top"> <input id="searchInput" name="search" accesskey="f" size="40" type="text"> <input name="go" class="searchButton" id="searchGoButton" value="Go" type="hidden"> </form>
                  </td>
                </tr>
              </tbody>
            </table>
          </td>
          <td width="50%" height="80%" align="center"> <br>
            <!-- BEGIN GENERAL LINKS -->
            <table width="80%" height="95%" cellpadding="2" border="0">
              <tbody>
                <tr>
                  <td width="55%" valign="top"> <a href="http://slashdot.org/" target="_top"><font size="3" face="arial"><i><b>Slashdot</b></i></font></a><br>
                  </td>
                  <td valign="top"> <a href="http://wwitv.com/"><span style="font-family: Arial;"><span style="text-decoration: underline;"><span style="font-style: italic;"><span style="font-weight: bold;">wwiTV.com</span></span></span></span></a><br>
                  </td>
                </tr>
                <tr>
                  <td valign="top"> <a href="http://www.genmay.net/" target="_top"><font size="3" face="arial"><i><b>Genmay</b></i></font></a><br>
                  </td>
                  <td valign="top"> <b><i><font face="Arial"> </font></i></b><a href="http://ineedpopcorn.com/"><span style="font-family: Arial;"><span style="text-decoration: underline;"><span style="font-style: italic;"><span style="font-weight: bold;">I Need Popcorn</span></span></span></span></a>
                  </td>
                </tr>
                <tr>
                  <td valign="top"> <a target="_top" href="https://my.orb.com/orb/?ks=boakes775"><font><i><b></b></i></font></a><font><i><b><a href="http://www.facebook.com/" target="_top"><font size="3" face="arial"><i><b>Facebook</b></i></font></a></b></i></font></td>
                  <td valign="top"> <a href="https://www.twitch.tv/"><span style="font-family: Arial;"><span style="text-decoration: underline;"><span style="font-style: italic;"><span style="font-weight: bold;">Twitch</span></span></span></span></a>
                  </td>
                </tr>
                <tr>
                  <td valign="top"> <a href="http://72.204.51.195:81/www.reddit.com" target="_top"><font><i><b><font><i><b></b></i></font></b></i></font></a><font><i><b><font><i><b><a href="http://www.reddit.com/" target="_top"><font size="3" face="arial"><i><b>Reddit</b></i></font></a></b></i></font></b></i></font>
                  </td>
                  <td valign="top"> <b><i><font face="Arial"> </font></i></b><font><i><b><a href="http://www.youtubetv.com/" target="_top"><font size="3" face="arial"><i><b>YouTubeTV</b></i></font></a></b></i></font>
                  </td>
                </tr>
                <tr>
                </tr>
                <tr>
                  <td valign="top"> <font size="3" face="arial"><i><b> <a target="_top" href="http://www.dictionary.com/">Dictionary</a></b></i></font><br>
                  </td>
                  <td valign="top"> <b><i><font face="Arial"> </font></i></b>
                    <b><i><font face="Arial"><a href="http://www.hulu.com/">Hulu</a></font></i></b></td>
                </tr>
                <tr>
                  <td valign="top"> <font size="3" face="arial"><i><b> <a target="_top" href="http://thesaurus.reference.com/">Thesaurus</a></b></i></font><br>
                  </td>
                  <td valign="top"> <b><i><font face="Arial"><a href="http://www.nasa.gov/multimedia/nasatv/index.html">NASA
                            TV</a></font></i></b></td>
                </tr>
                <tr>
                  <td valign="top"> <font size="3" face="arial"><i><b> </b></i></font><b><i><font face="Arial"><a href="http://www.woot.com/">Woot</a></font></i></b>
                  </td>
                  <td valign="top"> <a href="http://mail.uark.edu/"><b><i><font face="Arial"></font></i></b></a><b><i><font face="Arial"><a href="http://www.pandora.com/">Pandora</a></font></i></b>
                  </td>
                </tr>
                <tr>
                  <td valign="top"><b><i><font face="Arial"><a href="http://www.amazon.com/">Amazon</a></font></i></b>
                  </td>
                  <td valign="top"> <b><i><font face="Arial"><a href="http://listen.grooveshark.com/">Grooveshark</a></font></i></b>
                  </td>
                </tr>
                <tr>
                  <td valign="top"> <a href="https://idm.east.cox.net/coxlogin/ui/webmail?TARGET=-SM-https%3A%2F%2Fwebmail.east.cox.net"><font size="3" face="arial"><i><b>Cox.net Mail<br>
                          </b></i></font></a> </td>
                  <td valign="top"><b><i><font face="Arial"><a href="https://messages.google.com/web/">Google
                            SMS</a></font></i></b><b><i><font face="Arial"><a href="http://futurama-stream.com/">
                          </a></font></i></b></td>
                </tr>
                <tr>
                  <td valign="top"> <font size="3" face="arial"><i><b><a target="_top" href="http://www.gmail.com/">Gmail<br>
                          </a></b></i></font> </td>
                  <td valign="top"> <br>
                  </td>
                </tr>
              </tbody>
            </table>
          </td>
        </tr>
        <tr>
          <td valign="middle" align="center">
            <div class="GENXHwxNewStyle">
              <div class="OTDRHwxNewStyle"><a href="http://72.204.51.195:81/weather.html"><img alt="" src="http://sirocco.accuweather.com/nx_mosaic_400x300c/SIR/inmaSIRAR_.gif" style="border: 0px solid ; width: 374px; height: 311px;"></a></div>
            </div>
            <br>
          </td>
          <td valign="middle" align="center"><!-- BEGIN ADMIN LINKS -->
            <table width="90%" height="208" cellspacing="3" cellpadding="5" border="0">
              <tbody>
                <tr>
                  <td width="50%" bgcolor="#505a70"> <b><i><font face="Arial"><a href="https://wd5.myworkday.com/uasys/d/home.htmld">Workday</a></font></i></b></td>
                  <td bgcolor="#505a70"> <b><i><font face="Arial"><a href="http://www.arvest.com/">Arvest
                            Bank</a></font></i></b> </td>
                </tr>
                <tr>
                  <td bgcolor="#505a70"> <a href="http://www.myspace.com/"><b><i><font face="Arial"></font></i></b></a><b><i><font face="Arial"><a href="https://waprd2.uark.edu/web-apps/uits/leave/Main">Timesheet</a></font></i></b>
                  </td>
                  <td bgcolor="#505a70"> <b><i><font><b><i><font><a href="http://www.uarkfcu.com/"><b><i><font face="Arial">Uark Credit
                                        Union</font></i></b></a></font></i></b></font></i></b>
                  </td>
                </tr>
                <tr>
                  <td bgcolor="#505a70"> <b><i><font face="Arial"><a href="http://www.cnn.com/"><br>
                          </a></font></i></b> </td>
                  <td bgcolor="#505a70"><b><i><font><b><i><font><b><i><font><a href="https://westforkwaterandwastewater.ruralwaterusa.com/bill-payment-options"><b><i><font face="Arial">West Fork Water</font></i></b></a></font></i></b></font></i></b></font></i></b>
                  </td>
                </tr>
                <tr>
                  <td bgcolor="#505a70"> <br>
                  </td>
                  <td bgcolor="#505a70"> <font size="3" face="arial"><i><b><a target="_top" href="http://webmail.central.cox.net/"><br>
                          </a></b></i></font> </td>
                </tr>
                <tr>
                  <td bgcolor="#505a70"> <br>
                  </td>
                  <td bgcolor="#505a70"> <font size="3" face="arial"><i><b><a target="_top" href="http://www.statefarm.com/"><br>
                          </a></b></i></font> </td>
                </tr>
                <tr>
                  <td bgcolor="#505a70"> <br>
                  </td>
                  <td bgcolor="#505a70"> <br>
                  </td>
                </tr>
              </tbody>
            </table>
          </td>
        </tr>
      </tbody>
    </table>
  

</body></html>
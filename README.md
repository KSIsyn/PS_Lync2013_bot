PS_Lync2013_bot
===============

Description
===========

Powershell Lync bot for Lync 2013 client

Requirements to run
===================

MS Lync 2013 Client

MS Lync 2013 SDK Desktop API's (http://www.microsoft.com/en-us/download/details.aspx?id=36824)

  Microsoft.Office.UC.dll

  Microsoft.Lync.Model.dll (Desktop Version)

  Microsoft.Lync.controls.dll (Desktop Version) [can be saftly removed from code at this time this dll and its components are not in use]

MS .Net Framework 3.5 or 4 or Later Service pack

Avaiable Commands
=================

Convert-Rot13

Exit-LyncBot

Get-Hash

Register-LyncStateChange

Request-LyncSignin

Request-LyncSignout

Restart-LyncBot

Send-LyncMsg

Set-LyncAvailability

Start-LyncBot

Stop-LyncBot

Useage
======

Import-module './Lync Bot.psd1'

---
title: "Input Commands"
menu: "api"
menu:
  api:
    parent: "cli"
    title: "Input Commands"
---

{{% apiCard header="`jet input list`" example=`> jet input list
NAME         TYPE
/TTY/AMA0    Serial port
/TTY/AMA1    Serial port` %}}
List the available input devices. Any input listed on this page is available to pass into the `--input` flag.
{{% /apiCard %}}
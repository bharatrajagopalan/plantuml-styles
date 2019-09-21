# Styles for Plantuml

## Examples

You can try all of the below examples on http://www.plantuml.com/plantuml 

### Sequence Diagram


![Sequence](http://www.plantuml.com/plantuml/svg/POunKiGm34Lxdq9KL8dx57iFgXsj91A38mTBPeVR4vmXCE32C_xFJryFIIat5bZSDvjYh7WVv-HBkpMJIaLTr4SgQxmjMD4hlk1SDioeSTilRsiUp3-oM5pHN6eqUMkY95TEE5TSh_QQTDnQ23HSU88iRY3e0SdJExe01O3pmG7sm_qh5qXmtrl0IrU-46Q7z0pSWVsGGnikDC6Js73qpAKJoIQ7n4LC7_sS-izLH5o-8_cpbYX3-9NI9m00?sanitize=1)

```plantuml

!include https://raw.githubusercontent.com/bharatrajagopalan/plantuml-styles/master/sequence_diagram_skin.pu

c->d: lets eat
activate c
  activate d
    d->d: do i want to eat
    alt if d wants to eat
      d-->c: Yes- lets go
    else if d doesn't want to eat
      d-->c: naaah
      deactivate d
    end 
deactivate c
```

### Activity
![Activity](http://www.plantuml.com/plantuml/svg/LOunKWCn34Lxdq9qcu9r7mhISGbcF8fNMHkyif7aCClfSIY0D1x_BytJEwcXMD-AUyWSIry8abdJe_U2d_EQBVLpLv9OsOXjZdNpvuI29lY6QsrOa7qRputogBONKh-X6ed7QFcQRG_wddbk7PpxE-X-Vixb2qmlWYrTynTa7cqfj3mVm18nJ3lfmG4SczH8gZ2chxnaN0KtVN9Kb63YUhTJkUmZXw3qqOaZXG38ooX-ZGByOmpUvUPJcpkDCEo-0G00)

```plantuml
!include https://raw.githubusercontent.com/bharatrajagopalan/plantuml-styles/master/activity_skin.pu 

@startuml

start

if (Graphviz installed?) then (yes)
  :process all\ndiagrams;
else (no)
  :process only
  __sequence__ and __activity__ diagrams;
endif

stop
```


### Flowchart 

![Flowchart](http://www.plantuml.com/plantuml/svg/BOn13e8m44NtFOKUG9he3ZQe1p53cK2r3CtChuQ4mmlHpSz_USbh3QGeKtB7A26LdWyZaAtsNkbJ3H5ZwOgnXbd0WYhCa-z6KeBIauOvKoBnUPkzSZ8iYSrFP63r513V4Sl3Nb6gN9nRhwkhmOPc-xVL_U2yq_rlBerhMVgjzWK0)

```plantuml

!include https://raw.githubusercontent.com/bharatrajagopalan/plantuml-styles/master/activity_skin.pu

|A|
:test;

|B|

:test2;

|C|
:test3;
```





### Flowchart Ink theme

![Flowchart ink theme](http://www.plantuml.com/plantuml/svg/BSn1he8m4CRnVK_ntW6WYUvmWteGCvG9LChGTBvgI7fuItGpcL--vDyhA26lmVnxSI6F_3S3KJjh4xtRoMFEGrPERXEme7NRQeUP4Y7HawOjKY2niPwZqYZsm6fNKd2ovE1V7lj35o-DbwMDsPXoBQO3AoxrlnNpnUdG_RUSAtgMiIO_)

```plantuml

!include https://raw.githubusercontent.com/bharatrajagopalan/plantuml-styles/master/activity_skin-ink.pu

|A|
:test;

|B|

:test2;

|C|
:test3;
```

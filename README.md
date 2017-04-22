# AVU seminar

```crontab -e``` edituje casovatelne udalosti ve formatu

m h den(v mesici) mesic den(v tydnu), napr.:

*/5 * * * * /bin/sh /home/pi/run.sh

pro spusteni skriptu kazdych pet minut

@reboot /bin/sh /home/pi/run.sh

pro spusteni skriptu po restartu

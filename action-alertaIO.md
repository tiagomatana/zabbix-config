Subject: {TRIGGER.STATUS}: {TRIGGER.NAME}

Message: 
resource={HOST.NAME1}
event={TRIGGER.NAME}
environment=Production
severity={TRIGGER.SEVERITY}
status={TRIGGER.STATUS}
ack={EVENT.ACK.STATUS}
service={TRIGGER.HOSTGROUP.NAME}
group=Zabbix
value={ITEM.VALUE1}
text={TRIGGER.STATUS}: {TRIGGER.DESCRIPTION}
tags={EVENT.TAGS}
attributes.ip={HOST.IP1}
attributes.thresholdInfo={TRIGGER.TEMPLATE.NAME}: {TRIGGER.EXPRESSION}
type=zabbixAlert
dateTime={EVENT.DATE}T{EVENT.TIME}Z

# Windows Event Samples

This repo houses sample Windows event logs consisting of 338 distinct Event IDs.

Use this [Google Sheet](https://docs.google.com/spreadsheets/d/1kRmVt6PLz-xliD_Ynzz9W2FnJu7iYXSWjRl2SZ4CiaI/edit?usp=sharing) to view which Event IDs are available.

## Sample

#### EID 5156

```json
{
  "EventTime": "2021-08-27T13:03:47.002016+05:45",
  "Hostname": "IT01.corp.local",
  "Keywords": "9232379236109516800",
  "EventType": "AUDIT_SUCCESS",
  "SeverityValue": 2,
  "Severity": "INFO",
  "EventID": 5156,
  "SourceName": "Microsoft-Windows-Security-Auditing",
  "ProviderGuid": "{54849625-5478-4994-A5BA-3E3B0328C30D}",
  "Version": 1,
  "TaskValue": 12810,
  "OpcodeValue": 0,
  "RecordNumber": 4025408,
  "ExecutionProcessID": 4,
  "ExecutionThreadID": 2580,
  "Channel": "Security",
  "Message": "The Windows Filtering Platform has permitted a connection.\r\n\r\nApplication Information:\r\n\tProcess ID:\t\t2316\r\n\tApplication Name:\t\\device\\harddiskvolume2\\program files\\nxlog\\nxlog.exe\r\n\r\nNetwork Information:\r\n\tDirection:\t\tOutbound\r\n\tSource Address:\t\t192.168.2.46\r\n\tSource Port:\t\t49694\r\n\tDestination Address:\t192.168.4.132\r\n\tDestination Port:\t\t514\r\n\tProtocol:\t\t6\r\n\r\nFilter Information:\r\n\tFilter Run-Time ID:\t82874\r\n\tLayer Name:\t\tConnect\r\n\tLayer Run-Time ID:\t48",
  "Category": "Filtering Platform Connection",
  "Opcode": "Info",
  "ProcessID": "2316",
  "Application": "\\device\\harddiskvolume2\\program files\\nxlog\\nxlog.exe",
  "Direction": "%%14593",
  "SourceAddress": "192.168.2.46",
  "SourcePort": "49694",
  "DestAddress": "192.168.4.132",
  "DestPort": "514",
  "Protocol": "6",
  "FilterRTID": "82874",
  "LayerName": "%%14611",
  "LayerRTID": "48",
  "RemoteUserID": "S-1-0-0",
  "RemoteMachineID": "S-1-0-0",
  "EventReceivedTime": "2021-08-27T13:03:56.670598+05:45",
  "SourceModuleName": "in_win",
  "SourceModuleType": "im_msvistalog"
}
```
---
-api-id: M:Windows.ApplicationModel.VoiceCommands.VoiceCommandResponse.CreateResponse(Windows.ApplicationModel.VoiceCommands.VoiceCommandUserMessage)
-api-type: winrt method
---

<!-- Method syntax
public Windows.ApplicationModel.VoiceCommands.VoiceCommandResponse CreateResponse(Windows.ApplicationModel.VoiceCommands.VoiceCommandUserMessage userMessage)
-->

# Windows.ApplicationModel.VoiceCommands.VoiceCommandResponse.CreateResponse

## -description
Creates a [VoiceCommandResponse](voicecommandresponse.md) object used in calls to [ReportProgressAsync](voicecommandserviceconnection_reportprogressasync.md), [ReportSuccessAsync](voicecommandserviceconnection_reportsuccessasync.md) or [ReportFailureAsync](voicecommandserviceconnection_reportfailureasync.md).

## -parameters
### -param userMessage
The message that is spoken by **Cortana** and shown on the **Cortana** canvas. 
This message should be:

+ An informative statement on progress, completion, and error screens (see [ReportProgressAsync](voicecommandserviceconnection_reportprogressasync.md), [ReportSuccessAsync](voicecommandserviceconnection_reportsuccessasync.md), [ReportFailureAsync](voicecommandserviceconnection_reportfailureasync.md)).
+ An unambiguous question that can be answered with either yes or no on confirmation screens (see [RequestConfirmationAsync](voicecommandserviceconnection_requestconfirmationasync.md)).
+ A request for the user to select from the list of choices presented on disambiguation screens (see [RequestDisambiguationAsync](voicecommandserviceconnection_requestdisambiguationasync.md)).


## -returns
The response from the background app service for progress, completion, confirmation, or disambiguation screens displayed on the **Cortana** canvas.

## -remarks

## -examples

## -see-also
[CreateResponse(VoiceCommandUserMessage, IIterable(VoiceCommandContentTile))](voicecommandresponse_createresponse_493218068.md), [ elements and attributes v1.2](voice_command_elements_and_attributes_1_2.md), [Cortana interactions](http://msdn.microsoft.com/library/4c11a7cf-da26-4ca1-a9b9-fe52670101f5), [Cortana design guidelines](http://msdn.microsoft.com/library/a92c084b-9913-4718-9a04-569d51ace55d), [Cortana voice command sample](http://go.microsoft.com/fwlink/p/?LinkID=619899)
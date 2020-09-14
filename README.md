Coroutine Manager.

Declare;

    private Job conversationInProgress;

Kill:

    if (conversationInProgress != null) conversationInProgress.Kill();

Enable:

			conversationInProgress = new Job(ConversationDo(startIndex));
      
      


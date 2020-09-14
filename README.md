Coroutine Manager.

Kill coroutines instantly. 

Declare;

private Job thiscoroutine;

Kill:

if (thiscoroutine != null) thiscoroutine.Kill();

Enable:

thiscoroutine = new Job(thiscoroutine());

(Job is an IEnumerator)
      
      


# UnityTimer
Simple and easy to use Unity timer.

//All that is required to make a event that waits .5 seconds;
new Timer(.5f,()=>{Debug.Log("Hey that took .5 seconds")});

//It also supports awaiting which is done similarly
await Timer.Start(.5f);
```

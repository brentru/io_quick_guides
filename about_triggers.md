# Adafruit IO Triggers

*Wouldn't it be great if your data could perform actions based on their values?* Using Adafruit IO's **triggers**, you can be alerted of data values over email  (IO+ Users Only), over a webhook, or by another feed's value.

## Types of Triggers
Adafruit IO has two types of triggers: reactive triggers and scheduled triggers:

### Reactive Triggers

Reactive triggers **react to feed values**. You can perform a comparison between feeds, or a static value. Whenever the conditional is met, the trigger will perform an action such as emailing you, or setting another feed.

![reactive-trigger](https://i.imgur.com/Tnbk782.png)

### Scheduled Triggers

You can also schedule a trigger to email values of a feed at a specific time. This is especially useful if you want to check the state of a sensor.

![scheduled-trigger](https://i.imgur.com/lmI5qtw.png)
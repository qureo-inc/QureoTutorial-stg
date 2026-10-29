### @flyoutOnly true


# QureoMinecraft

## エージェントをうごかしてみよう！

みぎしたの![](https://raw.githubusercontent.com/qureo-inc/QureoTutorial/main/images/playbutton.png)をおそう！

```template
player.onChat("run", function () {
    while (true) {
        hiragana_agent.move(FORWARD, 1)
        if (hiragana_agent.detect(AgentDetection.Block, FORWARD) == true) {
            break;
        }
    }
})

```

```ghost
while (true) {
    hiragana_agent.move(FORWARD, 1)
    if (hiragana_agent.detect(AgentDetection.Block, FORWARD) == true) {
        break;
    }
}

```
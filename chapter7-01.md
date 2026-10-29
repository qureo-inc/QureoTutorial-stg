### @flyoutOnly true


# QureoMinecraft

## エージェントをうごかしてみよう！

みぎしたの![](https://raw.githubusercontent.com/qureo-inc/QureoTutorial/main/images/playbutton.png)をおしたあと、tキーをおしてrunといれてプログラムをうごかしてみよう！

```template
player.onChat("run", function () {
    if (hiragana_agent.inspect(AgentInspection.Block, DOWN) == GOLD_BLOCK) {
        hiragana_agent.turn(LEFT_TURN)
    }
})
```
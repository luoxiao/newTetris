<template>
  <div
        class="keyboard"
        :style="'margin-top:'+fillingNum+'px'"
      >
        <vbutton
          color="blue"
          size="s1"
          :top="0 + 10"
          :left="374 - 270"
          arrow="translate(0, 63px)"
          :position="true"
          :label="labelDropSpace"
          :active="keyboard['drop']"
          ref="dom_space"
        />
        <vbutton
          color="blue"
          size="s1"
          :top="180 + 10"
          :left="374 - 270"
          :label="labelDown"
          arrow="translate(0,-71px) rotate(180deg)"
          :active="keyboard['down']"
          ref="dom_down"
        />
        <vbutton
          color="blue"
          size="s1"
          :top="90 + 10"
          :left="284 - 270"
          :label="labelLeft"
          arrow="translate(60px, -12px) rotate(270deg)"
          :active="keyboard['left']"
          ref="dom_left"
        />
        <vbutton
          color="blue"
          size="s1"
          :top='90 + 10'
          :left='464 - 270'
          :label="labelRight"
          arrow="translate(-60px, -12px) rotate(90deg)"
          :active="keyboard['right']"
          ref="dom_right"
        />
        <vbutton
          color="blue"
          size="s0"
          :top="100"
          :left="52 + 310"
          :label="rotation"
          :active="keyboard['rotate']"
          ref="dom_rotate"
        />
        <vbutton
          color="red"
          size="s2"
          :top="0"
          :left="196 + 310"
          :label="labelResetR"
          :active="keyboard['reset']"
          ref="dom_r"
        />
        <vbutton
          color="green"
          size="s2"
          :top="0"
          :left="106 + 310"
          :label="labelSoundS"
          :active="keyboard['music']"
          ref="dom_s"
        />
        <vbutton
          color="green"
          size="s2"
          :top="0"
          :left="16 + 310"
          :label="labelPauseP"
          :active="keyboard['pause']"
          ref="dom_p"
        />
      </div>
</template>
<style lang="less">
 @import './index.less';
</style>

<script src="./index.js">
</script>

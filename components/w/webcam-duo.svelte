<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/i/ia4qhfxyu.css';
import '../../css/w/wqhnb6rty.css';
import '../../css/y/yn9vwmsxf.css';
import '../../css/b/b4tqxxbyg.css';
import '../../css/q/q04i72bzl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<g class="ft5dv1b6b"><path class="ia4qhfxyu"/><path clip-rule="evenodd" class="wqhnb6rty"/><path class="yn9vwmsxf"/><path class="b4tqxxbyg"/><path class="q04i72bzl"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-kameleon-color:webcam-duo" {...props}></Icon>

<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tczw_hbsg.css';
import '../../css/u/utt4xvbom.css';
import '../../css/q/qat37oo-m.css';
import '../../css/a/anga10bot.css';
import '../../css/z/zrmw_bcdh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="utt4xvbom wm-k"/><path class="qat37oo-m wm-a"/><path class="anga10bot wm-k"/><path class="wm-a zrmw_bcdh"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:swords-sketch" {...props}></Icon>

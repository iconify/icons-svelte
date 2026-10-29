<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tczw_hbsg.css';
import '../../css/j/j44rrabxi.css';
import '../../css/k/kabwe8a7o.css';
import '../../css/r/rolrwhb8t.css';
import '../../css/s/saig0paye.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="j44rrabxi"/><path class="kabwe8a7o wm-a"/><path class="rolrwhb8t wm-k"/><path class="saig0paye wm-a"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:shopping-bag-sketch" {...props}></Icon>

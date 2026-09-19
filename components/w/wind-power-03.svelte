<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jx0p4fbya.css';
import '../../css/m/mob0ae2zt.css';
import '../../css/n/n2sam2sks.css';
import '../../css/p/p-gpxkbpm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="jx0p4fbya"><path class="mob0ae2zt"/><path class="n2sam2sks"/><path class="p-gpxkbpm"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:wind-power-03" {...props}></Icon>

<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jx0p4fbya.css';
import '../../css/s/sw2wszxbb.css';
import '../../css/n/np4l_rbmm.css';
import '../../css/r/rw82l7faj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="jx0p4fbya"><path class="sw2wszxbb"/><path class="np4l_rbmm"/><path class="rw82l7faj"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:workflow-square-10" {...props}></Icon>

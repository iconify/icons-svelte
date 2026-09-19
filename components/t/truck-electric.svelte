<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jx0p4fbya.css';
import '../../css/r/rm_q7b7hi.css';
import '../../css/y/ydu9-nbzw.css';
import '../../css/v/vm23ifb4w.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="jx0p4fbya"><path class="rm_q7b7hi"/><path class="ydu9-nbzw"/><path class="vm23ifb4w"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:truck-electric" {...props}></Icon>

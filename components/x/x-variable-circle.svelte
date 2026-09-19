<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jx0p4fbya.css';
import '../../css/v/v5qcs8bop.css';
import '../../css/l/lr18s1wgn.css';
import '../../css/d/dawcsab1j.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="jx0p4fbya"><path class="v5qcs8bop"/><path class="lr18s1wgn"/><path class="dawcsab1j"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:x-variable-circle" {...props}></Icon>

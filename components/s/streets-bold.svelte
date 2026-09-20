<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cuyn6tgcc.css';
import '../../css/o/op24dvl4v.css';
import '../../css/h/hbcfabcbl.css';
import '../../css/r/rsqrtukoj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="op24dvl4v"/><path class="hbcfabcbl"/><path class="rsqrtukoj"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:streets-bold" {...props}></Icon>

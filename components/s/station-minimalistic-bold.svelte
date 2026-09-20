<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cuyn6tgcc.css';
import '../../css/f/fcke6rbgw.css';
import '../../css/x/xkxu1ibgd.css';
import '../../css/r/r_13o9i8m.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="fcke6rbgw"/><path class="xkxu1ibgd"/><path clip-rule="evenodd" class="r_13o9i8m"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:station-minimalistic-bold" {...props}></Icon>

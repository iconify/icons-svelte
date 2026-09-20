<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cuyn6tgcc.css';
import '../../css/k/kvw30zhji.css';
import '../../css/r/rpm6pjbrs.css';
import '../../css/y/y4d60-b-d.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="kvw30zhji"/><path class="rpm6pjbrs"/><path clip-rule="evenodd" class="y4d60-b-d"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:station-filled" {...props}></Icon>

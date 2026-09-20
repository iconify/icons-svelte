<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cuyn6tgcc.css';
import '../../css/x/xg1lcnbpv.css';
import '../../css/e/en376_own.css';
import '../../css/d/dk_5p9bho.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path clip-rule="evenodd" class="xg1lcnbpv"/><path clip-rule="evenodd" class="en376_own"/><path class="dk_5p9bho"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:translate2-filled" {...props}></Icon>

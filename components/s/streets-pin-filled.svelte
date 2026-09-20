<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cuyn6tgcc.css';
import '../../css/w/wg4_nqeyw.css';
import '../../css/w/wzyb7sccb.css';
import '../../css/n/nt6hy5b_b.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="wg4_nqeyw"/><path clip-rule="evenodd" class="wzyb7sccb"/><path class="nt6hy5b_b"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:streets-pin-filled" {...props}></Icon>

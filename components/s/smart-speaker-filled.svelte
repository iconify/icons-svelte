<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cuyn6tgcc.css';
import '../../css/i/i_u1o-blq.css';
import '../../css/u/ud6_-2m2a.css';
import '../../css/u/ufo48bitx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path clip-rule="evenodd" class="i_u1o-blq"/><path class="ud6_-2m2a"/><path class="ufo48bitx"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:smart-speaker-filled" {...props}></Icon>

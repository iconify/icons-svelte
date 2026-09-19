<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/w/wr5lmfzzp.css';
import '../../css/r/rr6yxmb6f.css';
import '../../css/c/crs0k7bit.css';
import '../../css/y/yw6_fjbsi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":80,"height":80};
const content = `<g class="ft5dv1b6b"><path class="wr5lmfzzp"/><path class="rr6yxmb6f"/><path class="crs0k7bit"/><path class="yw6_fjbsi"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs:running-duo" {...props}></Icon>

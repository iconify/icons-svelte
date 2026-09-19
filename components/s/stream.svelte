<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/ufeehvblu.css';
import '../../css/x/xr6selbya.css';
import '../../css/f/fsdcy2b0y.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":80,"height":80};
const content = `<g class="ufeehvblu"><path class="xr6selbya"/><path class="fsdcy2b0y"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs-poly:stream" {...props}></Icon>

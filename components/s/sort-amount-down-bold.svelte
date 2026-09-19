<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/h/h8nofnwha.css';
import '../../css/v/v1eiv24xr.css';
import '../../css/p/p7bg0ij5t.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":80,"height":80};
const content = `<g class="ft5dv1b6b"><path class="h8nofnwha"/><path class="v1eiv24xr"/><path class="p7bg0ij5t"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs:sort-amount-down-bold" {...props}></Icon>

<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/b/bue8_rb3u.css';
import '../../css/w/w13ubjbvr.css';
import '../../css/w/wdlx4qwzb.css';
import '../../css/i/ii4ionbci.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":300,"height":159};
const content = `<g class="ft5dv1b6b"><path class="bue8_rb3u"/><path class="w13ubjbvr"/><path class="wdlx4qwzb"/><path class="ii4ionbci"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cif:us" {...props}></Icon>

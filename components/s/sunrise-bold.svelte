<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/l/lu4k41tds.css';
import '../../css/o/o-ri9ache.css';
import '../../css/k/kj4rhbcdr.css';
import '../../css/a/aev_nzgxh.css';
import '../../css/s/soq33u-at.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":80,"height":80};
const content = `<g class="ft5dv1b6b"><path clip-rule="evenodd" class="lu4k41tds"/><path class="o-ri9ache"/><path class="kj4rhbcdr"/><path class="aev_nzgxh"/><path class="soq33u-at"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs:sunrise-bold" {...props}></Icon>

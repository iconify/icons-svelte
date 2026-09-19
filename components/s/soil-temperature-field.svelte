<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/h01tyzbfu.css';
import '../../css/y/y0pnzz87o.css';
import '../../css/g/gdr62dbcz.css';
import '../../css/l/lnplwwnva.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="h01tyzbfu"><path class="y0pnzz87o"/><path class="gdr62dbcz"/><path class="lnplwwnva"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:soil-temperature-field" {...props}></Icon>

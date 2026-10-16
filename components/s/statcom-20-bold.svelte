<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qoecip_zs.css';
import '../../css/u/u-2khd52i.css';
import '../../css/v/vysp5-ryk.css';
import '../../css/o/oheu1iy3h.css';
import '../../css/t/tspxr7b8c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="qoecip_zs"/><path class="u-2khd52i"/><path class="vysp5-ryk"/><path class="oheu1iy3h"/><path class="tspxr7b8c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:statcom-20-bold" {...props}></Icon>

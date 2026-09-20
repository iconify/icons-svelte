<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ipq1z-bjh.css';
import '../../css/l/lou2zl3dr.css';
import '../../css/p/p3_4el9va.css';
import '../../css/m/mc35szfhd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="lou2zl3dr"/><path class="p3_4el9va"/><path class="mc35szfhd"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:square-academic-cap-broken" {...props}></Icon>

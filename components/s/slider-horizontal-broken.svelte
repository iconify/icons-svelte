<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ipq1z-bjh.css';
import '../../css/t/ten2dqbwx.css';
import '../../css/o/oockgugaw.css';
import '../../css/a/axjtsp52f.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="ten2dqbwx"/><path class="oockgugaw"/><path class="axjtsp52f"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:slider-horizontal-broken" {...props}></Icon>

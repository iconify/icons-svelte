<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ipq1z-bjh.css';
import '../../css/s/sb0q3diim.css';
import '../../css/t/t3i0929hw.css';
import '../../css/n/noowh5fsj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="sb0q3diim"/><path class="t3i0929hw"/><path class="noowh5fsj"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:ruler-angular-line-duotone" {...props}></Icon>

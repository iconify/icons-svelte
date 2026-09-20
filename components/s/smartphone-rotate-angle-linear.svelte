<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ipq1z-bjh.css';
import '../../css/k/kzjab8bcu.css';
import '../../css/s/src5g-5zv.css';
import '../../css/a/ac1l4pbcd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="kzjab8bcu"/><path class="src5g-5zv"/><path class="ac1l4pbcd"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:smartphone-rotate-angle-linear" {...props}></Icon>

<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ipq1z-bjh.css';
import '../../css/g/g0v39tb0j.css';
import '../../css/c/c9seox20v.css';
import '../../css/t/tiuqf-byk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="g0v39tb0j"/><path class="c9seox20v"/><path class="tiuqf-byk"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:slider-horizontal-line-duotone" {...props}></Icon>

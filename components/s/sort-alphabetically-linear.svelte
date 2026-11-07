<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ipq1z-bjh.css';
import '../../css/i/i99jpsfam.css';
import '../../css/k/k_vfb7aeb.css';
import '../../css/h/hi5e58bpt.css';
import '../../css/o/o68l3dmms.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="i99jpsfam"/><path class="k_vfb7aeb"/><path class="hi5e58bpt"/><path class="o68l3dmms"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:sort-alphabetically-linear" {...props}></Icon>

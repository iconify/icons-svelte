<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ipq1z-bjh.css';
import '../../css/w/w37s95bcr.css';
import '../../css/n/ncu9ifj7a.css';
import '../../css/g/gz8ip2wkb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="w37s95bcr"/><path class="ncu9ifj7a"/><path class="gz8ip2wkb"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:three-squares-linear" {...props}></Icon>

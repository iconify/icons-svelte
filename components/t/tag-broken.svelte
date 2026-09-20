<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ipq1z-bjh.css';
import '../../css/i/iar3qwbrm.css';
import '../../css/e/epme-tb1k.css';
import '../../css/a/af-qgnuco.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="iar3qwbrm"/><path class="epme-tb1k"/><path class="af-qgnuco"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:tag-broken" {...props}></Icon>

<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ipq1z-bjh.css';
import '../../css/w/wb7_65b-g.css';
import '../../css/v/vkdts-b4s.css';
import '../../css/l/lzvosfbku.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="wb7_65b-g"/><path class="vkdts-b4s"/><path class="lzvosfbku"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:setting-done-04" {...props}></Icon>

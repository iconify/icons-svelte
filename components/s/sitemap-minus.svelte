<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/ril2l8bbu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ril2l8bbu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:sitemap-minus" {...props}></Icon>

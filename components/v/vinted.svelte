<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/w8x5-wb5s.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="w8x5-wb5s"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cbi:vinted" {...props}></Icon>

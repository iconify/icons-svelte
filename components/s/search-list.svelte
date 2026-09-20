<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xhun2cctq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="xhun2cctq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:search-list" {...props}></Icon>

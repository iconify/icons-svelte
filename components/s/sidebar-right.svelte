<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yt2ds61_u.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="yt2ds61_u"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="sidekickicons:sidebar-right" {...props}></Icon>

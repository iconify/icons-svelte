<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pq98g2brm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="pq98g2brm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:tiktok" {...props}></Icon>

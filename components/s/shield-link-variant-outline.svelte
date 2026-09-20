<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/utzmx2b3u.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="utzmx2b3u"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:shield-link-variant-outline" {...props}></Icon>

<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/i5m86r8df.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="i5m86r8df"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:shop-location-outline" {...props}></Icon>

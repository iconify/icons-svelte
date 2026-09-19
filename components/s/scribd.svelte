<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sejmm7sxs.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="sejmm7sxs"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:scribd" {...props}></Icon>

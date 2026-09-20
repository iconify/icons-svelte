<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/k-bfdpx9p.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="k-bfdpx9p"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:stopwatch-favorite-outline" {...props}></Icon>

<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pq3abbc4w.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="pq3abbc4w"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:speech-to-text-fill" {...props}></Icon>

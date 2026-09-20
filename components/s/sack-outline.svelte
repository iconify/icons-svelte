<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/njpmz0b0z.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="njpmz0b0z"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:sack-outline" {...props}></Icon>

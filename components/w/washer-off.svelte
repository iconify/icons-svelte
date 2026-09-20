<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/k4mvfjc7f.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="k4mvfjc7f"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:washer-off" {...props}></Icon>

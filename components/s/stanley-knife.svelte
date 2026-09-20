<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/l88_q8bvd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="l88_q8bvd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:stanley-knife" {...props}></Icon>

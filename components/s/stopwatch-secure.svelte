<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sphduib2i.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="sphduib2i"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:stopwatch-secure" {...props}></Icon>

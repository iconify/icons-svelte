<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/r-la4fbtf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="r-la4fbtf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:smoke-detector-variant" {...props}></Icon>

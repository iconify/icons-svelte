<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mrqz273dl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="mrqz273dl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoir:t-shirt" {...props}></Icon>

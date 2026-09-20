<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/snaob0bev.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="snaob0bev"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uil:thunderstorm-sun" {...props}></Icon>

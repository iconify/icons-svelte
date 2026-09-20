<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/soq9j-sgp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="soq9j-sgp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:ufo-2-line" {...props}></Icon>

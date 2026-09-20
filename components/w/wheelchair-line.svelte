<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pps2d9m7e.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="pps2d9m7e"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:wheelchair-line" {...props}></Icon>

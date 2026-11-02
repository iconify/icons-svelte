<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sc6tizw8s.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="sc6tizw8s"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:shield-shape-line" {...props}></Icon>

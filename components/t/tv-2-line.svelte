<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/oi2d1hbvy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="oi2d1hbvy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:tv-2-line" {...props}></Icon>

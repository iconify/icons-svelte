<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wje2n0b4i.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="wje2n0b4i"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoir:trekking" {...props}></Icon>

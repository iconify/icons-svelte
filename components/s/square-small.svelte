<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yfa-k33er.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="yfa-k33er"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:square-small" {...props}></Icon>

<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vcuhlcb9k.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="vcuhlcb9k"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair-light:tv-play" {...props}></Icon>

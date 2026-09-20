<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/ve6n4db7t.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ve6n4db7t"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:tv-box" {...props}></Icon>

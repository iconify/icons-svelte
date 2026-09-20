<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/l823r3h8t.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="l823r3h8t"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:sail-boat-sink" {...props}></Icon>

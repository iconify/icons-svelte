<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ilt0r1bny.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ilt0r1bny"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:size-extra-large" {...props}></Icon>

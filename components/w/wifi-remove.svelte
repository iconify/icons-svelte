<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rcn2f7bmz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="rcn2f7bmz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:wifi-remove" {...props}></Icon>

<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/e3903g84h.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="e3903g84h"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:select-remove" {...props}></Icon>

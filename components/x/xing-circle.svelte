<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/x1lm0bb4k.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="x1lm0bb4k"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:xing-circle" {...props}></Icon>

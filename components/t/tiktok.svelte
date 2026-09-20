<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yg8auor9g.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path class="yg8auor9g"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline:tiktok" {...props}></Icon>

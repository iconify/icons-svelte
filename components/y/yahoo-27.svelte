<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/m4r25c7hy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":30,"height":30};
const content = `<path class="m4r25c7hy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="wi:yahoo-27" {...props}></Icon>

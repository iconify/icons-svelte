<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/horqr3d3u.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":2048,"height":2048};
const content = `<path class="horqr3d3u"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent-mdl2:semibold-weight" {...props}></Icon>

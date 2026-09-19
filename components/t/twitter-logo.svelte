<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/urg8vg02i.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":2048,"height":2048};
const content = `<path class="urg8vg02i"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent-mdl2:twitter-logo" {...props}></Icon>

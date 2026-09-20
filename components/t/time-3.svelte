<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kpm1h9bjw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":30,"height":30};
const content = `<path class="kpm1h9bjw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="wi:time-3" {...props}></Icon>

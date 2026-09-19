<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kvgrnpbwz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":680,"height":810};
const content = `<path class="kvgrnpbwz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="il:url" {...props}></Icon>

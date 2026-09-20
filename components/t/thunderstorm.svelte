<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fnb5mtbyb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":30,"height":30};
const content = `<path class="fnb5mtbyb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="wi:thunderstorm" {...props}></Icon>

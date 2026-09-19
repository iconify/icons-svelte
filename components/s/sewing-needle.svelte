<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gw62veb9j.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="gw62veb9j"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent-emoji-high-contrast:sewing-needle" {...props}></Icon>

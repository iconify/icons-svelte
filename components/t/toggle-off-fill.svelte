<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wczda7yij.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="wczda7yij"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:toggle-off-fill" {...props}></Icon>

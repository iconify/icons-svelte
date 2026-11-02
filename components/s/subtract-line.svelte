<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/ys2zd9bbc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ys2zd9bbc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:subtract-line" {...props}></Icon>

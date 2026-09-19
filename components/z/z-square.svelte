<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/u2wgzk62w.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1792,"height":1792};
const content = `<path class="u2wgzk62w"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vs:z-square" {...props}></Icon>

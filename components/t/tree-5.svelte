<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fxu01r5zg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":80,"height":80};
const content = `<path class="fxu01r5zg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs:tree-5" {...props}></Icon>

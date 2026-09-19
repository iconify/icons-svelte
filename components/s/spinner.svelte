<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/ji7iwovju.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":80,"height":80};
const content = `<path class="ji7iwovju"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs:spinner" {...props}></Icon>

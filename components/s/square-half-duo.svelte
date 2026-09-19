<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/o3r2cj34a.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":80,"height":80};
const content = `<path class="o3r2cj34a"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs:square-half-duo" {...props}></Icon>

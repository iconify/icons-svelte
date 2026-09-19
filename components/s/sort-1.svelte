<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xcf3m5b1z.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":80,"height":80};
const content = `<path class="xcf3m5b1z"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs:sort-1" {...props}></Icon>

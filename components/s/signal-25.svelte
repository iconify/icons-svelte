<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cj7gr_b9p.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":80,"height":80};
const content = `<path class="cj7gr_b9p"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs:signal-25" {...props}></Icon>

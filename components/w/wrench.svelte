<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s__lwjb_t.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":80,"height":80};
const content = `<path class="s__lwjb_t"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs:wrench" {...props}></Icon>

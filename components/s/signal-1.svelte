<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/np0tqyb7w.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":80,"height":80};
const content = `<path class="np0tqyb7w"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs:signal-1" {...props}></Icon>

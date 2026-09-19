<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/w2bvri4qz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":80,"height":80};
const content = `<path class="w2bvri4qz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs:signal-2" {...props}></Icon>

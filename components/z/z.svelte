<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s1vqtqi0b.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":80,"height":80};
const content = `<path class="s1vqtqi0b"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs-poly:z" {...props}></Icon>

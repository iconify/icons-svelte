<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/z5uub3b9w.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":80,"height":80};
const content = `<path class="z5uub3b9w"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs:watch-2" {...props}></Icon>

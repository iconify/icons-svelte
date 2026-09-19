<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ivepwjbjv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":80,"height":80};
const content = `<path class="ivepwjbjv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs:watch-1-bold" {...props}></Icon>

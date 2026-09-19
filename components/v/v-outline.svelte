<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/u-nqzrbwg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":80,"height":80};
const content = `<path class="u-nqzrbwg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs:v-outline" {...props}></Icon>

<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kk_1t8jzv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":80,"height":80};
const content = `<rect class="kk_1t8jzv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs:stop-bold" {...props}></Icon>

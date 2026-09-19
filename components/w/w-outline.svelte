<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/noi34ubfp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":80,"height":80};
const content = `<path class="noi34ubfp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs:w-outline" {...props}></Icon>

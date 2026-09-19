<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cci7y7bwp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":80,"height":80};
const content = `<path class="cci7y7bwp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs:square-half" {...props}></Icon>

<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/eppudwb7t.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":80,"height":80};
const content = `<path class="eppudwb7t"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs:watch-2-bold" {...props}></Icon>

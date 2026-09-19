<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/f9107n9gb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":17,"height":16};
const content = `<path class="f9107n9gb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="si-glyph:umbrella-close" {...props}></Icon>

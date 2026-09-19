<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nax1ayx-j.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":17,"height":16};
const content = `<path class="nax1ayx-j"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="si-glyph:tag" {...props}></Icon>

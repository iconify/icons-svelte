<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/i9y7tdhpd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":17,"height":16};
const content = `<path class="i9y7tdhpd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="si-glyph:umbrella-open" {...props}></Icon>

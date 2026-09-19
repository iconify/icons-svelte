<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nna_jvqox.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":17,"height":16};
const content = `<path class="nna_jvqox"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="si-glyph:tent-camp" {...props}></Icon>

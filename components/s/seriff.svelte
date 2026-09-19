<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/i1gttdbvr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":17,"height":16};
const content = `<path class="i1gttdbvr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="si-glyph:seriff" {...props}></Icon>

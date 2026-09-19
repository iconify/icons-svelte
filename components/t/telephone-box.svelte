<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rxn3dhv8k.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="rxn3dhv8k"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="si-glyph:telephone-box" {...props}></Icon>

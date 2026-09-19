<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/j1loo9bkg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":17,"height":16};
const content = `<path class="j1loo9bkg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="si-glyph:two-arrow-down" {...props}></Icon>

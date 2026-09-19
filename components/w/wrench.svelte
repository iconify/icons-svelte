<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jefc31vvu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":17,"height":16};
const content = `<path class="jefc31vvu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="si-glyph:wrench" {...props}></Icon>

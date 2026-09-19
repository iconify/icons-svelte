<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/q8z_ehb6c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":17,"height":16};
const content = `<path class="q8z_ehb6c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="si-glyph:stove" {...props}></Icon>

<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fck1plbjy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":17,"height":16};
const content = `<path class="fck1plbjy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="si-glyph:wind-turbines" {...props}></Icon>

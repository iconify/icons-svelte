<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mc3_pqumv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":17,"height":16};
const content = `<path class="mc3_pqumv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="si-glyph:square-delicious" {...props}></Icon>

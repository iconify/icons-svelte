<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/oo1bv_b1p.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":11,"height":11};
const content = `<path class="oo1bv_b1p"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="maki:suitcase-11" {...props}></Icon>

<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vtpy_02bv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="vtpy_02bv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:utah-with-capital-star" {...props}></Icon>

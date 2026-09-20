<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/t_h4-1b1d.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="t_h4-1b1d"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:south-carolina-with-capital-star" {...props}></Icon>

<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lf_j2_b2d.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="lf_j2_b2d"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:scis-control-tower" {...props}></Icon>

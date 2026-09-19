<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/khql2o0xz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":12,"height":12};
const content = `<path class="khql2o0xz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="garden:stamp-stroke-12" {...props}></Icon>

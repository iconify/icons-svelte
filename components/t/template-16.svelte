<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/t0bvf-bxy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="t0bvf-bxy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="nonicons:template-16" {...props}></Icon>

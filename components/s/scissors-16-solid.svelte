<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/d28tlbcov.css';
import '../../css/r/r173rlbez.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="d28tlbcov"/><path class="r173rlbez"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="heroicons:scissors-16-solid" {...props}></Icon>

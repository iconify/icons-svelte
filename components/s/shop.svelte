<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/oq8nqq2ik.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="oq8nqq2ik"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bi:shop" {...props}></Icon>

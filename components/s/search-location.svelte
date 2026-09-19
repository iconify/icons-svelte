<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/k_f3imouw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":640,"height":640};
const content = `<path class="k_f3imouw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa7-solid:search-location" {...props}></Icon>

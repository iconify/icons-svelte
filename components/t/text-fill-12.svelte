<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/u9li6fwhq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":12,"height":12};
const content = `<path class="u9li6fwhq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="garden:text-fill-12" {...props}></Icon>

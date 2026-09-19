<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/uea3qtb-k.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="uea3qtb-k"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icomoon-free:text-width" {...props}></Icon>

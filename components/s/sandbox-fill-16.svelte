<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hzcfu_bvm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="hzcfu_bvm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="garden:sandbox-fill-16" {...props}></Icon>

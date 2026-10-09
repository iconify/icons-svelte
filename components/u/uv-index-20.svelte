<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/x3ul-itcf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="x3ul-itcf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:uv-index-20" {...props}></Icon>

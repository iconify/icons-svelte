<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/f4ncvtbxj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="f4ncvtbxj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="garden:wrap-left-fill-16" {...props}></Icon>

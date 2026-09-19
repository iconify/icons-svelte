<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/z8gxk74en.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="z8gxk74en"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="garden:shapes-fill-16" {...props}></Icon>

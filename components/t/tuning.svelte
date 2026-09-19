<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fzvnzzbkf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="fzvnzzbkf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:tuning" {...props}></Icon>

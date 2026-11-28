<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/i8bvzkb2i.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":256,"height":256};
const content = `<path class="i8bvzkb2i"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pullo:stack-simple-check-light" {...props}></Icon>

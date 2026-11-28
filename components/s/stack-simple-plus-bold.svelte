<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/klj372b0v.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":256,"height":256};
const content = `<path class="klj372b0v"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pullo:stack-simple-plus-bold" {...props}></Icon>

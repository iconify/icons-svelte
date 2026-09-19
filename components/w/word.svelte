<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/d0c0s1bpx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="d0c0s1bpx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icons8:word" {...props}></Icon>

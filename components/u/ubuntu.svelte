<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jfn798b0v.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="jfn798b0v"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bi:ubuntu" {...props}></Icon>

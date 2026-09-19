<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cy-1rpbyx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1024,"height":833};
const content = `<path class="cy-1rpbyx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="whh:shell" {...props}></Icon>

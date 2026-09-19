<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zv9w3mbgc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":271,"height":512};
const content = `<path class="zv9w3mbgc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="file-icons:scratch" {...props}></Icon>

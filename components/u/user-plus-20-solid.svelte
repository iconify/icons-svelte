<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pyeu8actj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="pyeu8actj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="heroicons:user-plus-20-solid" {...props}></Icon>

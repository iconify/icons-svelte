<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/ln3ktcb3i.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="ln3ktcb3i"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:shield-off-20" {...props}></Icon>

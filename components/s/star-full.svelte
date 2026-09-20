<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/t7_67ke_d.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="t7_67ke_d"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="zondicons:star-full" {...props}></Icon>

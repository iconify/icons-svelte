<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/t34a1hbvh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="t34a1hbvh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bxl:vk" {...props}></Icon>

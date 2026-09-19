<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/j_8m3-boe.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="j_8m3-boe"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:underline-dashed-filled" {...props}></Icon>

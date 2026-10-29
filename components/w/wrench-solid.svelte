<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zgcclkiel.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="zgcclkiel"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:wrench-solid" {...props}></Icon>

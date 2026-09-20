<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/x1-gz_pwy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="x1-gz_pwy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:star-s-line" {...props}></Icon>

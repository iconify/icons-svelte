<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/repgmct4u.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="repgmct4u"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vadivam:superscript" {...props}></Icon>

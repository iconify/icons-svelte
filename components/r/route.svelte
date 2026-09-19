<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zrtjap9eu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="zrtjap9eu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa6-solid:route" {...props}></Icon>

<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vmh_ty2ao.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1200,"height":1200};
const content = `<path class="vmh_ty2ao"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="el:step-backward" {...props}></Icon>

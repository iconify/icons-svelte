<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/v_0o3568j.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="v_0o3568j"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="raphael:trash" {...props}></Icon>

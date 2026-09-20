<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vq7uilbjo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":21,"height":21};
const content = `<path class="vq7uilbjo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="system-uicons:split-three" {...props}></Icon>

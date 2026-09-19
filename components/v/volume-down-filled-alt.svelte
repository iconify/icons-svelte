<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tlfcf80ar.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="tlfcf80ar"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:volume-down-filled-alt" {...props}></Icon>

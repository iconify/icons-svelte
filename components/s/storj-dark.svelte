<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vk3v_nvcc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="vk3v_nvcc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:storj-dark" {...props}></Icon>

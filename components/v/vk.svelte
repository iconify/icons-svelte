<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/l_-knnm4g.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="l_-knnm4g"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="la:vk" {...props}></Icon>

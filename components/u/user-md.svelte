<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/e0u7a7bcm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":640,"height":640};
const content = `<path class="e0u7a7bcm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa7-solid:user-md" {...props}></Icon>

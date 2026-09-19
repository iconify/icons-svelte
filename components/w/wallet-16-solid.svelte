<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bz0vkbces.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="bz0vkbces"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="heroicons:wallet-16-solid" {...props}></Icon>

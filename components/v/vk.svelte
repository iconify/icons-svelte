<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cem9iobou.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1952,"height":1280};
const content = `<path class="cem9iobou"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa:vk" {...props}></Icon>

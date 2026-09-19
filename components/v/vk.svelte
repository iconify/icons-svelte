<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vi9qqdnqh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="vi9qqdnqh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cib:vk" {...props}></Icon>

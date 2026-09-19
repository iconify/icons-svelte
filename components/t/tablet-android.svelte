<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/p3ed8os0k.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":384,"height":512};
const content = `<path class="p3ed8os0k"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="zmdi:tablet-android" {...props}></Icon>

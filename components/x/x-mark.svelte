<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yfqzyy89q.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path clip-rule="evenodd" class="yfqzyy89q"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="heroicons-solid:x-mark" {...props}></Icon>

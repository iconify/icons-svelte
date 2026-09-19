<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yktp6pbrf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path clip-rule="evenodd" class="yktp6pbrf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="heroicons-solid:x-circle" {...props}></Icon>

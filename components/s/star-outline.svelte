<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/x_jz5xwqo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="x_jz5xwqo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="famicons:star-outline" {...props}></Icon>

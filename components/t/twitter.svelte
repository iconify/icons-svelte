<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/v--lvvb6q.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":432,"height":384};
const content = `<path class="v--lvvb6q"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="zmdi:twitter" {...props}></Icon>

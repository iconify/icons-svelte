<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sk593vdev.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="sk593vdev"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:trumpet" {...props}></Icon>

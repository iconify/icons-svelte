<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nw0cxs7kf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="nw0cxs7kf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="temaki:windmill" {...props}></Icon>

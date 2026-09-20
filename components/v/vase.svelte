<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/p-w7kybcy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="p-w7kybcy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="temaki:vase" {...props}></Icon>

<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/exn835bum.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":448,"height":512};
const content = `<path class="exn835bum"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa6-solid:square-share-nodes" {...props}></Icon>

<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nhc0pb2vu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":328,"height":512};
const content = `<path class="nhc0pb2vu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ps:watch" {...props}></Icon>

<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/ln9yij2wi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path clip-rule="evenodd" class="ln9yij2wi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ix:unlock-plant" {...props}></Icon>

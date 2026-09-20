<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bpf71yarp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="bpf71yarp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:two-one-one" {...props}></Icon>

<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/iocgcpb9m.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":8,"height":8};
const content = `<path class="iocgcpb9m"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="oi:warning" {...props}></Icon>

<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wr9aydbhj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="wr9aydbhj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:smallstep-light" {...props}></Icon>

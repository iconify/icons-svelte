<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yvty72j-v.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="yvty72j-v"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa-solid:vector-square" {...props}></Icon>

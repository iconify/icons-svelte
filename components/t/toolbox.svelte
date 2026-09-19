<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yq37tkb4h.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="yq37tkb4h"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa6-solid:toolbox" {...props}></Icon>

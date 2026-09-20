<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yslno4_-j.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="yslno4_-j"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:tirreno-light" {...props}></Icon>

<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/ygo7n3bmd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="ygo7n3bmd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:tirreno-dark" {...props}></Icon>

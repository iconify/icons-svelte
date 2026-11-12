<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bl1k8xx3a.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="bl1k8xx3a"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:stoat-dark" {...props}></Icon>

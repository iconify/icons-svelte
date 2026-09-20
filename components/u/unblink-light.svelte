<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nrvuy5biy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="nrvuy5biy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:unblink-light" {...props}></Icon>

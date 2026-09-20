<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sh90gerbl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="sh90gerbl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:vodia-dark" {...props}></Icon>

<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nch_dfbxs.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="nch_dfbxs"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa-solid:th-list" {...props}></Icon>

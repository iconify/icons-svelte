<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nz2fis0uk.css';
import '../../css/v/v2kg9llkn.css';
import '../../css/z/z0e_fjb2q.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="nz2fis0uk"/><path class="v2kg9llkn"/><path class="z0e_fjb2q"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:whodb-light" {...props}></Icon>

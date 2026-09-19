<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/d0b0pkckb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="d0b0pkckb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa-solid:search" {...props}></Icon>

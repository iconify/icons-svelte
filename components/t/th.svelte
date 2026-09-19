<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/uio5m4bmb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":640,"height":640};
const content = `<path class="uio5m4bmb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa7-solid:th" {...props}></Icon>

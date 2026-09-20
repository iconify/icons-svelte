<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/uwde3obxb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="uwde3obxb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lsicon:vip-consume-filled" {...props}></Icon>

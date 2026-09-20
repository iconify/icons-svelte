<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/y9tlm85hd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="y9tlm85hd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lsicon:scan-filled" {...props}></Icon>

<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/a8670_bex.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="a8670_bex"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lsicon:top-filled" {...props}></Icon>

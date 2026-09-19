<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/z194h6bnl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1408,"height":1792};
const content = `<path class="z194h6bnl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa:volume-control-phone" {...props}></Icon>

<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vxn6wcoog.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":640,"height":512};
const content = `<path class="vxn6wcoog"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa-brands:wix" {...props}></Icon>

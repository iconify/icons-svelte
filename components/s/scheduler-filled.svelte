<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/y93mowbxk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="y93mowbxk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ix:scheduler-filled" {...props}></Icon>

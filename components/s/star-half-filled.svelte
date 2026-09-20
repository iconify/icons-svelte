<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vks6qxb6e.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path clip-rule="evenodd" class="vks6qxb6e"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ix:star-half-filled" {...props}></Icon>

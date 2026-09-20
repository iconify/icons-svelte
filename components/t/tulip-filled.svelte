<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/a15fqzbix.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="a15fqzbix"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ix:tulip-filled" {...props}></Icon>

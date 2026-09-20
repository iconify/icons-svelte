<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tdom5rbim.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="tdom5rbim"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:steamdb" {...props}></Icon>

<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sn3wbh0ei.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":330,"height":512};
const content = `<path class="sn3wbh0ei"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="file-icons:solidity" {...props}></Icon>

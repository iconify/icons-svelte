<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sc0n45fmc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="sc0n45fmc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="file-icons:shippable" {...props}></Icon>

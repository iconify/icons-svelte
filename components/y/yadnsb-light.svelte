<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/l04_dfhcz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="l04_dfhcz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:yadnsb-light" {...props}></Icon>

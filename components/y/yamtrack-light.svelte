<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hclia1bkf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="hclia1bkf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:yamtrack-light" {...props}></Icon>

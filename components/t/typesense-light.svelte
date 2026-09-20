<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xfv2j2qkp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="xfv2j2qkp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:typesense-light" {...props}></Icon>

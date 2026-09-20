<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/aeetxvtyv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="aeetxvtyv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:twingate" {...props}></Icon>

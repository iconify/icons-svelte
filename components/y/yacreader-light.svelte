<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/ptw17bc-m.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="ptw17bc-m"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:yacreader-light" {...props}></Icon>

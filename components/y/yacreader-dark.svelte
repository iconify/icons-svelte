<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rf4-oobbd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="rf4-oobbd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:yacreader-dark" {...props}></Icon>

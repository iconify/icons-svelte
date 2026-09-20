<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/oto715bfm.css';
import '../../css/g/gnj61ac6v.css';
import '../../css/o/orctz5b3e.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="oto715bfm"/><path class="gnj61ac6v"/><path class="orctz5b3e"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:smore-newsletter" {...props}></Icon>

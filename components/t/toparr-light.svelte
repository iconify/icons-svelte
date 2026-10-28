<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/smq3h324s.css';
import '../../css/l/lb5y2fbti.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="smq3h324s"/><path class="lb5y2fbti"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:toparr-light" {...props}></Icon>

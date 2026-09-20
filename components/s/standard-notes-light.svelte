<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vc_p1acct.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="vc_p1acct"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:standard-notes-light" {...props}></Icon>

<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rzxio8blc.css';
import '../../css/t/tsv_okbow.css';
import '../../css/i/ij824bc0n.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="rzxio8blc"/><path class="tsv_okbow"/><circle class="ij824bc0n"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:rurdesk-dark" {...props}></Icon>

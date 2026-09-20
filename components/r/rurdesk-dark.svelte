<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rg676pb3g.css';
import '../../css/t/tsv_okbow.css';
import '../../css/s/sclwzib1q.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="rg676pb3g"/><path class="tsv_okbow"/><circle class="sclwzib1q"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:rurdesk-dark" {...props}></Icon>

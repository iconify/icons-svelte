<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/ss1_jtd_n.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="ss1_jtd_n"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:securo" {...props}></Icon>

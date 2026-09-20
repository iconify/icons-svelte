<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/awm_sxbcl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="awm_sxbcl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:ubiquiti-unifi-light" {...props}></Icon>

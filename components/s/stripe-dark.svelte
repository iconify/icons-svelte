<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sm_xptbgw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="sm_xptbgw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:stripe-dark" {...props}></Icon>

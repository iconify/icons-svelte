<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/t1cwtbc5g.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="t1cwtbc5g"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:self-hosted-gateway-light" {...props}></Icon>

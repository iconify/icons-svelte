<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sghq9ybsb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="sghq9ybsb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:self-hosted-gateway-dark" {...props}></Icon>

<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dxz5dc_of.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="dxz5dc_of"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:signoz-dark" {...props}></Icon>

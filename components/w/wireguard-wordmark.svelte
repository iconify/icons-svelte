<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vpg-nubov.css';
import '../../css/f/fhcl44oal.css';
import '../../css/q/qijlvrbjb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":128,"height":128};
const content = `<path class="vpg-nubov"/><path class="fhcl44oal"/><path class="qijlvrbjb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="devicon:wireguard-wordmark" {...props}></Icon>

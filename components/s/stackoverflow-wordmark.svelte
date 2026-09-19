<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/iqapy4bsh.css';
import '../../css/u/uy44wxbxz.css';
import '../../css/n/n230x8b_n.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":128,"height":128};
const content = `<path class="iqapy4bsh"/><path class="uy44wxbxz"/><path class="n230x8b_n"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="devicon:stackoverflow-wordmark" {...props}></Icon>

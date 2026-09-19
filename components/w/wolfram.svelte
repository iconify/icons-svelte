<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nx_um_bgw.css';
import '../../css/w/w1n9wrt_a.css';
import '../../css/g/genqieb0u.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":128,"height":128};
const content = `<path class="nx_um_bgw"/><path class="w1n9wrt_a"/><path class="genqieb0u"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="devicon:wolfram" {...props}></Icon>

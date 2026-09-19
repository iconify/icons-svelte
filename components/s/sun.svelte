<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mwu80rb7x.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="mwu80rb7x"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cil:sun" {...props}></Icon>

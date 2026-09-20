<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/iq39e_bxv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="iq39e_bxv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="nimbus:user" {...props}></Icon>

<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/c95rs2b_n.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="c95rs2b_n"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:scrutiny-dark" {...props}></Icon>

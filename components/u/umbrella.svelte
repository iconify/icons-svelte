<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xrm7n2blh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":576,"height":512};
const content = `<path class="xrm7n2blh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa-solid:umbrella" {...props}></Icon>

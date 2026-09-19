<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ifjm3fbay.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":384,"height":384};
const content = `<path class="ifjm3fbay"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="zmdi:texture" {...props}></Icon>

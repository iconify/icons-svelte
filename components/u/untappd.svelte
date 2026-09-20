<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wfvlv_bdi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="wfvlv_bdi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="la:untappd" {...props}></Icon>

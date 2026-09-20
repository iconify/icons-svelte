<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sn3oon7iq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="sn3oon7iq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="raphael:thunder" {...props}></Icon>

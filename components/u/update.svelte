<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/w3_ip_ivq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":8,"height":8};
const content = `<path class="w3_ip_ivq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="picon:update" {...props}></Icon>

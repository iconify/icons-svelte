<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xjpn_9bah.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":8,"height":8};
const content = `<path class="xjpn_9bah"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="oi:vertical-align-center" {...props}></Icon>

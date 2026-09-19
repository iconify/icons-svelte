<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hnckt6bpn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="hnckt6bpn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bitcoin-icons:star-outline" {...props}></Icon>

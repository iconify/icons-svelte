<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/keccfcbyk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="keccfcbyk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:signal-wifi-3-line" {...props}></Icon>

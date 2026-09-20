<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ipdg89bcn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ipdg89bcn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:signal-wifi-3-fill" {...props}></Icon>

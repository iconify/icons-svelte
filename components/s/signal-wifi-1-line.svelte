<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/npo_yhygr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="npo_yhygr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:signal-wifi-1-line" {...props}></Icon>

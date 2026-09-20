<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/upqvygbki.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="upqvygbki"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:signal-wifi-2-line" {...props}></Icon>

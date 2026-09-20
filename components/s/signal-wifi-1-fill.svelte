<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/b5-36r0an.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="b5-36r0an"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:signal-wifi-1-fill" {...props}></Icon>

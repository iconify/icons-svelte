<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nyfg24c1h.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="nyfg24c1h"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:unpin-fill" {...props}></Icon>

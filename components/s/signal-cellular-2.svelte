<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/n6k5uxbxd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="n6k5uxbxd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:signal-cellular-2" {...props}></Icon>

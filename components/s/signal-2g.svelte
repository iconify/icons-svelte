<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/evqb2ybga.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="evqb2ybga"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:signal-2g" {...props}></Icon>

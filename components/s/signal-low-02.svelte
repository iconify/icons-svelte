<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xmbi7nb1n.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="xmbi7nb1n"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:signal-low-02" {...props}></Icon>

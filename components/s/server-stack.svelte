<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/p454a_g3k.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="p454a_g3k"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="heroicons:server-stack" {...props}></Icon>

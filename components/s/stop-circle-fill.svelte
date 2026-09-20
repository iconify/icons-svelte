<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pr3vqhb6h.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="pr3vqhb6h"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:stop-circle-fill" {...props}></Icon>

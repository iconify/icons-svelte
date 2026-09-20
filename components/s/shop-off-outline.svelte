<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hg0y7c3_u.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="hg0y7c3_u"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:shop-off-outline" {...props}></Icon>

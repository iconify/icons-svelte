<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/khpwbvb_u.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="khpwbvb_u"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:shield-heart-solid" {...props}></Icon>

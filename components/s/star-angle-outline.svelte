<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fb-9d2bep.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="fb-9d2bep"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:star-angle-outline" {...props}></Icon>

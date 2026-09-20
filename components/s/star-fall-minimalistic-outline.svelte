<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fb6ezbbdi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="fb6ezbbdi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:star-fall-minimalistic-outline" {...props}></Icon>

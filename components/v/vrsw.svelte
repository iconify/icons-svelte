<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vw2nn3blf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="vw2nn3blf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="token:vrsw" {...props}></Icon>

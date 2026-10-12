<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pi8rx-aqc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="pi8rx-aqc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide-extended:utensils-filled" {...props}></Icon>

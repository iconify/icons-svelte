<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hm_y01bmo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="hm_y01bmo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:window-round" {...props}></Icon>

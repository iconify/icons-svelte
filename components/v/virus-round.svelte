<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qu-hdfbug.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="qu-hdfbug"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:virus-round" {...props}></Icon>

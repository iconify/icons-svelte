<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pvy8izgsh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="pvy8izgsh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="simple-icons:webhint" {...props}></Icon>

<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/h3gfd-2ey.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="h3gfd-2ey"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:sri-lanka" {...props}></Icon>

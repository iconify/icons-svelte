<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/m808873ny.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="m808873ny"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:tsunami-20-bold" {...props}></Icon>

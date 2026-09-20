<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pcoy1k6ny.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path clip-rule="evenodd" class="pcoy1k6ny"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ix:unlock-plant-filled" {...props}></Icon>

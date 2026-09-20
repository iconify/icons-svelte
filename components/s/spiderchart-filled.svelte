<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tlekx8bij.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path clip-rule="evenodd" class="tlekx8bij"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ix:spiderchart-filled" {...props}></Icon>

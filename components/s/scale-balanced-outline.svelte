<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tlxal_o3t.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="tlxal_o3t"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="flowbite:scale-balanced-outline" {...props}></Icon>

<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/eet5ssb1j.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="eet5ssb1j"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="flowbite:star-half-stroke-solid" {...props}></Icon>

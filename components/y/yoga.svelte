<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/m4ahsbc3p.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="m4ahsbc3p"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:yoga" {...props}></Icon>

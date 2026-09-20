<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/ho_oqbcml.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ho_oqbcml"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:xrp-fill" {...props}></Icon>

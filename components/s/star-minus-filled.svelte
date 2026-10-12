<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fjms-oqvl.css';
import '../../css/v/v2tmeobir.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="fjms-oqvl"/><path class="v2tmeobir"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide-extended:star-minus-filled" {...props}></Icon>

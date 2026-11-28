<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/w6-agqbwn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="w6-agqbwn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair-light:wallet-check" {...props}></Icon>

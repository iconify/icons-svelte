<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ipztmvqbp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ipztmvqbp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:sun" {...props}></Icon>

<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/n67foqbgg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="n67foqbgg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:square-arrow-left-round" {...props}></Icon>

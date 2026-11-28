<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rlbkapxxg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="rlbkapxxg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair:workflow-gear" {...props}></Icon>

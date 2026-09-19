<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fws4g4j_k.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="fws4g4j_k"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:timeline-list" {...props}></Icon>

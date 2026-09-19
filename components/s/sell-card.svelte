<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tqa_9q7yj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="tqa_9q7yj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:sell-card" {...props}></Icon>
